# 📊 Integrated QA Test Log & Bug Tracker: CV Page

**QA Lead:** Yuliya  
**Status:** In Progress (Bugs Found, Awaiting Fixes) 🛠️  

| ID | Test Description (Что тестируем) | Initial Result (Результат сейчас) | Fix Description (Что исправили) | Final Result (Результат после исправления) |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Check layout responsiveness on mobile screens (Ensure no horizontal scroll appears) | **FAILED** ❌ (The page shakes and moves horizontally on mobile initial load). | *Awaiting developer fix...* | *Not tested yet* |
| **2** | Verify that the video container scales correctly on mobile devices and doesn't cut off | **FAILED** ❌ (YouTube video player width is fixed and forces the layout to stretch). | *Awaiting developer fix...* | *Not tested yet* |
| **3** | Verify that navigation buttons don't overlap text on different screen sizes | **PASSED** ✅ (All elements and text remain clearly readable and do not collide). | *No fix needed* | **PASSED** ✅ |
| **4** | Verify that clicking the "Expand" button smoothly opens the menu. | **FAILED** ❌ (Tapping fields causes forceful browser auto-zoom, hiding layout borders). | *Awaiting developer fix...* | *Not tested yet* |
| **5** |  Verify that clicking the "Collapse" button closes the menu. | **PASSED** ✅ (Browser 'Please fill out this field' popup works correctly). | *No fix needed* | **PASSED** ✅ |
| **6** | Stress test: Rapidly click the menu button 10 times to check code stability. | **FAILED** ❌ (Inoperable due to double-tap zoom blocker. Button moves away). | *Awaiting developer fix...* | *Not yet tested* |
| **7** | Verify that the video player plays content correctly upon clicking the Play button. | **FAILED** ❌ (Real photos are missing; technical grey 250*250 blocks are shown). | *Awaiting developer fix...* | *Not yet tested* |
| **8** | Gallery layout stability on refresh | **PASSED** ✅ (The grid structure is stable and doesn't flicker on refresh). | *No fix needed* | **PASSED** ✅ |
| **9** | Images adaptation to desktop fullscreen | **PASSED** ✅ (Excellent grid. Items stack vertically on mobile, horizontally on desktop). | *No fix needed* | **PASSED** ✅ |
| **10** | Phone number link `+79778657543` click | **PASSED** ✅ (Triggers native system popup with 'Call / Cancel' options). | *No fix needed* | **PASSED** ✅ |
| **11** | Email link `it@mail.ru` click | **PASSED** ✅ (Instantly opens the default system mail application). | *No fix needed* | **PASSED** ✅ |
| **12** | Contact links click in Offline mode | **PASSED** ✅ (Apps open successfully. OS handles offline with standard alerts). | *No fix needed* | **PASSED** ✅ |
