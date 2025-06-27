fix: handling null data in CommunityInfo and added loading before data is not yet loaded

- Added a check to prevent crash when data is not yet loaded
- Introduced loading while fetching /cosc.json
- Improved error handling for fetch failures
- Ensured safe rendering of community details after successful fetch
