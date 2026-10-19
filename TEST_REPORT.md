# 📂 QA Test Execution Report: CV Page

**QA Lead:** Yuliya  
**Status:** In Progress 🚀  

---

## 📱 Block 1: UI & Layout Testing (Size and Responsiveness)

- [ ] **Test 1:** **FAILED** The page shakes and moves horizontally on mobile initial load. User has to pinch-to-zoom out to make it fit the screen.
- [ ] **Test 2:** **FAILED** The YouTube video player width is fixed and does not scale down on mobile screens. It forces the whole webpage to stretch horizontally, causing the layout to shake.
- [ ] **Test 3:** **PASSED** All text elements, lists, and form fields remain clearly readable and do not overlap or collide on mobile view.

---

## 🎛️ Block 2: Functional Testing (Menu & Buttons)

- [ ] **Test 4:** **FAILED** On mobile, tapping an input field causes the browser to forcefully auto-zoom. The input rectangle expands beyond the screen edges, hiding the layout borders. This happens because the input font size is likely below 16px.
- [ ] **Test 5:** **PASSED** The form validation works correctly. Clicking 'Submit' with empty fields triggers a browser validation popup 'Please fill out this field' above the First Name input, preventing empty submission.
- [ ] **Test 6:** **FAILED** Inoperable on mobile due to zoom blocker. After the 2nd rapid tap, the browser triggers 'double-tap to zoom', the entire screen scales up forcefully, and the layout shakes. The button moves away from the user's finger, blocking further testing.

---

## 🎬 Block 3: Media Testing (Gallery Images)

- [ ] **Test 7:** **FAILED** The real gallery images are missing/broken. The page currently displays generic grey technical placeholders '250*250' instead of actual project screenshots or photos.
- [ ] **Test 8:** **PASSED** The gallery grid structure is highly stable. Refreshing the webpage multiple times does not cause any layout shifting, flickering, or distortion of the container blocks.
- [ ] **Test 9:** **PASSED** Excellent responsive behavior. The gallery items successfully change orientation: they stack vertically on mobile screens and align perfectly in a horizontal row on desktop without any image stretching or quality los).

---

## ✉️ Block 4: Contact Information Testing

- [ ] **Test 10:** Click on the Phone number `+79778657543` to check if it triggers a mobile call application (`tel:` link).
- [ ] **Test 11:** Click on the Email link `it@mail.ru` to check if it opens the default email client (`mailto:` link).
- [ ] **Test 12:** Negative test: Click on contact links while the network is disconnected (Offline mode).
