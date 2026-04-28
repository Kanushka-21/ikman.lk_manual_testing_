# Test Report - ikman.lk Website

## Executive Summary
Manual testing exercise on ikman.lk website to improve testing knowledge. Completed 27 test cases across 6 modules. All tests passed (100% pass rate).

## Test Execution Summary

| Metric | Value |
|--------|-------|
| Total Test Cases | 27 |
| Passed | 27 |
| Failed | 0 |
| Pass Rate | 100% |
| Execution Date | April 28, 2026 |

## Results by Module

### Authentication (AUTH) - 5 Tests
| Test | Result |
|------|--------|
| Valid mobile login | Pass |
| Invalid OTP | Pass |
| Empty mobile validation | Pass |
| Google login | Pass |
| Session persistence | Pass |

**Summary:** All authentication features working correctly.

### Ad Posting (AD) - 6 Tests
| Test | Result |
|------|--------|
| Post ad with valid data | Pass |
| Required fields validation | Pass |
| Image upload | Pass |
| Invalid file upload | Pass |
| Negative price validation | Pass |
| Post without login | Pass |

**Summary:** All ad posting functionality and validation working as expected.

### Search (SRCH) - 5 Tests
| Test | Result |
|------|--------|
| Search with keyword | Pass |
| No results message | Pass |
| Category filter | Pass |
| Location filter | Pass |
| Multiple filters | Pass |

**Summary:** Search and filter features working correctly.

### Listing (LIST) - 4 Tests
| Test | Result |
|------|--------|
| Item details page | Pass |
| Images display | Pass |
| Contact seller | Pass |
| Save item | Pass |

**Summary:** All listing features working as intended.

### Negative Tests (NEG) - 5 Tests
| Test | Result |
|------|--------|
| Empty search | Pass |
| Invalid phone number | Pass |
| Long description | Pass |
| Duplicate ad | Pass |
| Special characters | Pass |

**Summary:** All edge cases handled correctly.

### Confirmation (CON) - 2 Tests
| Test | Result |
|------|--------|
| Ad visible to others | Pass |
| Real buyer contact | Pass |

**Summary:** Ad visibility and communication working as expected.

## Key Findings

### Strengths
- All core features functioning properly
- Form validation working correctly
- File upload restrictions enforced
- Session management stable
- Filter functionality accurate
- User protection (login required for posting)

### Issues Found
- None

## Conclusion
This testing exercise covered core functionality of ikman.lk. Learning outcomes: Understanding test case design, test execution, documentation, result tracking, and test reporting. All 27 test cases passed successfully.

## Learning Points
1. Test case design and structure
2. Testing different modules systematically
3. Recording test results accurately
4. Identifying test categories (positive, negative, edge cases)
5. Creating test documentation
6. Understanding pass/fail criteria

---
**Report Date:** April 28, 2026  
**Tester:** Kanushka Witharamage  
**Status:** Approved
