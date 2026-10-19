# 📂 QA Test Execution Report: CV Page

**QA Lead:** Yuliya  
**Status:** In Progress 🚀  

---

## 📱 Block 1: UI & Layout Testing (Size and Responsiveness)

- [ ] **Test 1:** Check layout responsiveness on mobile screens. Ensure NO horizontal scroll appears (the page shouldn't shake left to right).
- [ ] **Test 2:** Verify that the 3 placeholder images container in the Gallery scales correctly on mobile devices and text doesn't cut off.
- [ ] **Test 3:** Verify that buttons and text elements (like "Skills" list or "Submit" button) don't overlap text on different screen sizes.

---

## 🎛️ Block 2: Functional Testing (Menu & Buttons)

- [ ] **Test 4:** Verify that the form fields receive focus smoothly when clicked.
- [ ] **Test 5:** Verify the behavior of the `Submit` button when clicked.
- [ ] **Test 6:** Stress test: Rapidly click the `Submit` button 10 times to check code and page stability.

---

## 🎬 Block 3: Media Testing (Gallery Images)

- [ ] **Test 7:** Verify that all 3 placeholder images load correctly (no broken image icons).
- [ ] **Test 8:** Verify that the layout of the gallery remains stable and doesn't break upon page refresh.
- [ ] **Test 9:** Verify if images adapt well to full-screen desktop mode without losing quality or stretching.

---

## ✉️ Block 4: Contact Information Testing

- [ ] **Test 10:** Click on the Phone number `+79778657543` to check if it triggers a mobile call application (`tel:` link).
- [ ] **Test 11:** Click on the Email link `it@mail.ru` to check if it opens the default email client (`mailto:` link).
- [ ] **Test 12:** Negative test: Click on contact links while the network is disconnected (Offline mode).
