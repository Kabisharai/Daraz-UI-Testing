# Daraz Search Functionality — Test Notes

## Scope
Testing the search bar on Daraz homepage and results page.

## Test Cases

### TC-001: Basic keyword search
- **Action:** Enter "headphones" in the search bar and press Enter
- **Expected:** Results page loads with relevant products
- **Status:** Not yet executed

### TC-002: Search with special characters
- **Action:** Enter "headphones!!!" in the search bar
- **Expected:** System handles gracefully — either filters results or shows no-results message
- **Status:** Not yet executed

### TC-003: Empty search submission
- **Action:** Click the search button without entering any text
- **Expected:** No crash; page either stays or shows a prompt
- **Status:** Not yet executed

### TC-004: Search result sorting
- **Action:** Search "laptop", then sort by "Price: Low to High"
- **Expected:** Results reorder correctly with lowest price first
- **Status:** Not yet executed

## Notes
- Search is a high-traffic flow — defects here affect nearly all users
- Edge cases (empty input, special characters) are commonly missed in manual testing
