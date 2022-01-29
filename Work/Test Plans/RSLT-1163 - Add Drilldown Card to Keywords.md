# [RSLT-1163](https://user-testing.atlassian.net/browse/RSLT-1163)
![[rslt_1163_01.png]]
## Acceptance Criteria
1. if the user has keyword_maps_v2 flag enabled: clicking on a keyword map bubble opens the dropdown card.
2. if the user has keyword_maps_v2 flag disabled: clicking on a keyword map bubble still opens a popover.
3. dropdown contains information on the screenshot.
4. dropdown can be collapsed by pressing X, which unfocuses the keyword.
## Test Plan
- [x] The acceptance criteria is met
- [x] No console errors
- [x] Known bug: open the drilldown card, switch to the Individual responses tab, and then switch back to KWM tab - this will lead to a console error