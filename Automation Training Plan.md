# 🧭 Automation Testing Learning Plan
### Playwright-First · TypeScript · CI/CD · 2026 Edition

> **Framework Decision:** This plan focuses on **Playwright** as the primary automation framework.
> As of 2026, Playwright leads with **45.1% adoption** among QA professionals, **78,600+ GitHub stars**, and the highest job market demand for modern automation roles. It is backed by Microsoft, supports TypeScript/JavaScript/Python/Java/C#, runs cross-browser (Chromium, Firefox, WebKit), and is the top choice for modern SDET roles.
>
> Cypress is covered as a **secondary skill** (still widely used in front-end teams). Selenium is covered as a **supplemental skill** for enterprise/legacy environments.

---

## 📊 Progress Dashboard

![Overall](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-overall.json)

### Weekly Progress

![Week 0](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week0.json)
![Week 2](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week2.json)
![Week 3](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week3.json)
![Week 4](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week4.json)
![Week 5](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week5.json)
![Week 6](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week6.json)
![Week 7](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week7.json)
![Week 8](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week8.json)
![Week 9](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week9.json)
![Week 10](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week10.json)
![Week 11](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week11.json)
![Week 12](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week12.json)
![Week 13](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week13.json)
![Week 14](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week14.json)
![Week 15](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week15.json)
![Week 16](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week16.json)

Track your progress by checking off tasks with `[x]` as you complete them.

| Phase | Weeks | Focus |
|---|---|---|
| 🔵 Foundation | 0–1 | JavaScript for Testers |
| 🔵 Core Framework | 2–4 | Playwright Fundamentals |
| 🔵 Intermediate | 5–6 | TypeScript + Framework Design |
| 🟡 Advanced | 7–8 | Advanced Playwright + API Testing |
| 🟡 Integration | 9 | CI/CD + GitHub Actions |
| 🔴 Portfolio | 10 | Real Project + Portfolio |
| ➕ Supplemental | 11–12 | Cypress (Secondary) |
| ➕ Supplemental | 13–14 | Selenium (Enterprise/Legacy) |
| ➕ Supplemental | 15 | Mobile Testing with Appium |
| ➕ Supplemental | 16 | AI-Assisted Testing |

---

# 📚 TABLE OF CONTENTS

- [Why Playwright?](#-why-playwright)
- [Setup](#️-setup)
- [Git Basics](#-git-basics-required)
- [How to Use This Plan](#-how-to-use-this-daily-plan)
- [WEEK 0–1: JavaScript Foundation](#-week-01-javascript-for-testers-foundation)
- [WEEK 2–4: Playwright Fundamentals](#-week-24-playwright-fundamentals)
- [WEEK 5–6: TypeScript + Framework Design](#-week-56-typescript--framework-design)
- [WEEK 7–8: Advanced Playwright + API Testing](#-week-78-advanced-playwright--api-testing)
- [WEEK 9: CI/CD + GitHub Actions](#-week-9-cicd--github-actions)
- [WEEK 10: Portfolio Project](#-week-10-portfolio-project)
- [SUPPLEMENTAL Week 11–12: Cypress](#-supplemental-week-1112-cypress-secondary-skill)
- [SUPPLEMENTAL Week 13–14: Selenium](#-supplemental-week-1314-selenium-enterpriselegacy)
- [SUPPLEMENTAL Week 15: Mobile Testing (Appium)](#-supplemental-week-15-mobile-testing-with-appium)
- [SUPPLEMENTAL Week 16: AI-Assisted Testing](#-supplemental-week-16-ai-assisted-testing)
- [Next Steps](#-next-steps--career-roadmap)
- [Common Mistakes](#️-common-mistakes)
- [Interview Prep](#-interview-prep-cheat-sheet)

---

# 🏆 Why Playwright?

| Factor | Playwright | Cypress | Selenium |
|---|---|---|---|
| **2026 Adoption** | 45.1% ✅ | 14.4% | 22.1% (declining) |
| **GitHub Stars** | 78,600+ ✅ | ~50,000 | ~32,000 |
| **Job Market** | Fastest growing ✅ | Steady | Legacy enterprise |
| **Speed** | Fastest ✅ | Medium | Slowest |
| **Cross-browser** | Chrome, Firefox, WebKit ✅ | Chrome, Firefox (limited Safari) | All (via drivers) |
| **Languages** | JS, TS, Python, Java, C# ✅ | JS/TS only | Many |
| **Mobile** | Yes (native) ✅ | No | Via Appium |
| **Parallel Execution** | Free, built-in ✅ | Paid (Cloud) | Via Selenium Grid |
| **Flaky Tests** | Lowest (auto-wait) ✅ | Medium | Highest |
| **Backed by** | Microsoft ✅ | Cypress.io | Open Source |

**Verdict:** Playwright is the clear choice for new learners in 2026 targeting modern SDET/QA Automation roles.

---

# ⚙️ SETUP

Install the following:
- Node.js (LTS version) → https://nodejs.org
- Git → https://git-scm.com
- VS Code → https://code.visualstudio.com

Create accounts:
- GitHub → https://github.com

Verify installation:
```bash
node -v
npm -v
git --version
```

**VS Code Extensions (install all):**
- ESLint
- Prettier
- Playwright Test for VSCode (by Microsoft) ← essential
- GitLens
- Path Intellisense

---

# 🔧 GIT BASICS (REQUIRED)

Learn:
- `git init`
- `git add .`
- `git commit -m "message"`
- `git push`
- `git pull`
- `git branch`
- `git checkout -b feature/branch-name`

**Exercise — Your First Repo:**
- [ ] Create a GitHub account
- [ ] Create a repository called `automation-training`
- [ ] Clone it locally
- [ ] Create a `hello.js` file
- [ ] Push it to GitHub

**Bonus Exercise:**
- [ ] Create a `.gitignore` file and add `node_modules/` to it
- [ ] Create a `README.md` and describe what you're learning
- [ ] Push both files and verify on GitHub

---

# 🧭 HOW TO USE THIS DAILY PLAN

**Each day (1 hour):**
- 15 min → Read/watch the linked resource
- 45 min → Code the tasks and exercises

**Always:**
- Push code to GitHub after each session
- Write 1–3 notes (what you learned / struggled with)
- Tick `[x]` on completed checkboxes

**💡 DEBUGGING RULE — follow this order:**
1. Read the full error message carefully
2. Add `console.log()` to debug values
3. Search the exact error in Google or the official docs
4. Break the problem into smaller pieces — don't solve everything at once
5. If stuck for 20+ minutes, move on and come back later

---

# 🔵 WEEK 0–1: JavaScript for Testers (FOUNDATION)
![Week 0](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week0.json)

📚 Resources: [JavaScript.info](https://javascript.info) · [MDN Web Docs](https://developer.mozilla.org)

---

## 🟢 DAY 1 – Variables + Console

### LEARN:
- [ ] What is a variable?
- [ ] Difference between const and let

### DO:
- [ ] Create variables: `username`, `password`, `isLoggedIn`, `attempts`
- [ ] Print all values using `console.log()`
- [ ] Try changing a `const` and observe the error

### EXERCISES:
```js
// Exercise 1: Basic variables
const username = "admin";
const password = "1234";
let isLoggedIn = false;
let attempts = 0;

console.log(username, password, isLoggedIn, attempts);

// Exercise 2: Type checking
console.log(typeof username);   // "string"
console.log(typeof isLoggedIn); // "boolean"
console.log(typeof attempts);   // "number"

// Exercise 3: String template literals
const greeting = `Hello, ${username}! You have ${attempts} login attempts.`;
console.log(greeting);
```

### CHALLENGE:
- [ ] Create a variable for `maxAttempts = 3`
- [ ] Print a message: `"Remaining attempts: X"` using template literals
- [ ] Try to reassign a `const` — read and explain the error

### OUTPUT:
- [ ] 6+ variables created
- [ ] 1 JS file committed to GitHub

### Notes:
```
// Write what you learned here
```

---

## 🟢 DAY 2 – Functions

### LEARN:
- [ ] What is a function?
- [ ] Parameters and return values

### DO:
- [ ] Create `login(username, password)` returning `true` or `false`
- [ ] Create an arrow function version of the same

### EXERCISES:
```js
// Exercise 1: Regular function
const validUsername = "admin";
const validPassword = "1234";

function login(username, password) {
  if (username === validUsername && password === validPassword) {
    return true;
  }
  return false;
}

console.log(login("admin", "1234"));  // true
console.log(login("wrong", "1234")); // false

// Exercise 2: Arrow function
const loginArrow = (username, password) =>
  username === validUsername && password === validPassword;

console.log(loginArrow("admin", "1234")); // true

// Exercise 3: Function with default parameters
function greetUser(name = "Guest", role = "viewer") {
  return `Welcome, ${name}! Your role is: ${role}`;
}

console.log(greetUser("Cedric", "admin"));
console.log(greetUser()); // uses defaults
```

### CHALLENGE:
- [ ] Create a `logout()` function that returns `"Logged out successfully"`
- [ ] Create a `validatePassword(password)` function that checks if password length is at least 8 characters
- [ ] Call all three functions and log the results

### OUTPUT:
- [ ] 4+ working functions (regular + arrow)
- [ ] File committed

### Notes:
```
// Write what you learned here
```

---

## 📅 DAY 3 – Arrays

### LEARN:
- [ ] Arrays and looping concepts
- [ ] map() and filter()

### DO:
- [ ] Create an array of user objects
- [ ] Use `map()`, `filter()`, `find()`

### EXERCISES:
```js
const users = [
  { username: "admin",   role: "admin",  active: true  },
  { username: "cedric",  role: "user",   active: true  },
  { username: "testbot", role: "user",   active: false },
  { username: "manager", role: "manager",active: true  },
];

// Exercise 1: filter active users
const activeUsers = users.filter(user => user.active);
console.log("Active:", activeUsers);

// Exercise 2: get only usernames using map
const usernames = users.map(user => user.username);
console.log("Usernames:", usernames);

// Exercise 3: find a specific user
const found = users.find(user => user.username === "cedric");
console.log("Found:", found);

// Exercise 4: count active users
console.log("Active count:", activeUsers.length);

// Exercise 5: forEach
users.forEach(user => {
  console.log(`${user.username} (${user.role}) - Active: ${user.active}`);
});
```

### CHALLENGE:
- [ ] Filter only `"admin"` role users
- [ ] Create a new array with only `{ username, active }` properties (use `map`)
- [ ] Check if ANY inactive user exists using `.some()`

### OUTPUT:
- [ ] 5+ array operations working

---

## 📅 DAY 4 – Objects (VERY IMPORTANT)

### LEARN:
- [ ] Object structure
- [ ] Accessing properties

### DO:
- [ ] Create a `user` object with multiple properties
- [ ] Read, update, and delete properties

### EXERCISES:
```js
// Exercise 1: Create and modify object
const user = {
  username: "admin",
  password: "1234",
  role: "admin",
  active: true,
  loginCount: 0
};

user.role = "superadmin";      // update
user.loginCount += 1;          // increment
delete user.password;          // delete
console.log(user);

// Exercise 2: Destructuring
const { username, role, active } = user;
console.log(`${username} is a ${role}. Active: ${active}`);

// Exercise 3: Nested object
const testConfig = {
  baseUrl: "https://www.saucedemo.com",
  credentials: {
    valid:   { username: "standard_user", password: "secret_sauce" },
    invalid: { username: "wrong_user",    password: "wrong_pass"   },
    locked:  { username: "locked_out_user", password: "secret_sauce" }
  },
  timeouts: { short: 3000, medium: 5000, long: 10000 }
};

console.log(testConfig.credentials.valid.username);
console.log(testConfig.timeouts.medium);
```

### CHALLENGE:
- [ ] Add a method `getDisplayName()` to the user object that returns `"username (role)"`
- [ ] Create a `testData` object containing both valid AND invalid login credentials
- [ ] Destructure the nested credentials and print them

### OUTPUT:
- [ ] Object with nested data created and manipulated

---

## 📅 DAY 5 – Combine Arrays + Objects

### LEARN:
- [ ] Real-world data structures

### DO:
- [ ] Create test data:
  multiple users with roles

### EXERCISE:
- [ ] Filter admin users
- [ ] Get usernames only

```
const users = [
  { username: "admin", role: "admin" },
  { username: "user1", role: "user" }
];

// Filter for users expected to fail
const failingUsers = testUsers.filter(u => u.expectedResult !== "success");
console.log("Users that should fail:", failingUsers);

// Exercise 2: Spread operator
const baseUser = { role: "user", active: true };
const adminUser = { ...baseUser, username: "admin", role: "admin" };
console.log(adminUser);

// Exercise 3: Simulate test data lookup
function getTestUser(expectedResult) {
  return testUsers.find(u => u.expectedResult === expectedResult);
}

const successUser = getTestUser("success");
console.log("Use for success test:", successUser.username);
```

### CHALLENGE:
- [ ] Add a `description` property to each test user explaining what is being tested
- [ ] Create a function `getUsersByResult(result)` that returns all users matching that expected result
- [ ] Print a formatted summary of all test users

---

## 📅 DAY 6 – Async/Await (CRITICAL FOR PLAYWRIGHT)

### LEARN:
- [ ] What is async/await?
- [ ] Why async matters in testing

### DO:
- [ ] Create async function returning data

### EXERCISE:
- [ ] Simulate API call (setTimeout or promise)

```
function fetchUser() {
  return new Promise(resolve => {
    setTimeout(() => {
      if (id > 0) {
        resolve({ id, username: `user_${id}`, active: true });
      } else {
        reject(new Error("Invalid user ID"));
      }
    }, 500);
  });
}

// Exercise 2: Async/await with try-catch (ALWAYS use this pattern)
async function loadUser(id) {
  try {
    const user = await fetchUserFromDB(id);
    console.log("Loaded user:", user);
    return user;
  } catch (error) {
    console.error("Error loading user:", error.message);
    return null;
  }
}

loadUser(1);   // success
loadUser(-1);  // triggers error

// Exercise 3: Multiple async operations
async function loadMultipleUsers() {
  const ids = [1, 2, 3];
  const users = await Promise.all(ids.map(id => fetchUserFromDB(id)));
  console.log("All users:", users);
}

loadMultipleUsers();
```

### CHALLENGE:
- [ ] Create an async function `simulateLogin(username, password)` that resolves after 1 second with `{ success: true }` if credentials match, or rejects with an error if not
- [ ] Call it with both valid and invalid credentials using `try/catch`

---

## 📅 DAY 7 – Mini Project: Login System Simulator

### BUILD: A command-line login simulator

### REQUIREMENTS:
- [ ] Array of valid users stored as objects
- [ ] `login(username, password)` function (async)
- [ ] Handles: valid login, wrong password, locked account, max attempts (3)
- [ ] All functions use `async/await`
- [ ] Committed to GitHub

```js
// Starter structure — complete the rest yourself
const users = [
  { username: "admin",       password: "admin123",   role: "admin",  locked: false },
  { username: "standard",    password: "pass123",    role: "user",   locked: false },
  { username: "lockeduser",  password: "pass123",    role: "user",   locked: true  },
];

let attempts = {};

async function login(username, password) {
  // TODO: Check if user exists
  // TODO: Check if user is locked
  // TODO: Check if attempts exceeded
  // TODO: Validate password
  // TODO: Return appropriate result
}

async function runTests() {
  console.log(await login("admin", "admin123"));     // success
  console.log(await login("admin", "wrongpass"));    // wrong password
  console.log(await login("lockeduser", "pass123")); // locked
  console.log(await login("ghost", "pass123"));      // not found
}

runTests();
```

---

## 🧪 TESTING FUNDAMENTALS (BEFORE PLAYWRIGHT)

Learn the theory before writing tests:
- [ ] What is a test case?
- [ ] Assertion vs verification
- [ ] Positive vs negative testing
- [ ] Test data management
- [ ] Flaky tests (what & why)

Exercise:
- [ ] Write 5 manual test cases for login feature

---

# 🔵 WEEK 2: Cypress Basics
![Week 2](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week2.json)

📚 Use:
- Cypress Documentation

🌐 TEST SITES:
- https://www.saucedemo.com (login/e-commerce)
- https://demo.playwright.dev/todomvc (todo app)
- https://jsonplaceholder.typicode.com (API testing)
- https://reqres.in (REST API practice)

---
![Week 2](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week2.json)

## WEEK 2, DAY 1 – Install + First Test

### LEARN:
- [ ] What is Cypress?
- [ ] Test structure (describe, it)

### DO:
- [ ] Install Cypress
- [ ] Run sample test

```
npm init -y
npm install cypress --save-dev
npx cypress open
```

### OUTPUT:
- [ ] Playwright installed
- [ ] 2 passing tests
- [ ] HTML report viewed

---

## WEEK 2, DAY 2 – Locators (THE MOST IMPORTANT SKILL)

### LEARN:
- [ ] cy.visit
- [ ] cy.get

### DO:
- [ ] Open a demo site
- [ ] Check page loads

### EXERCISE:
- [ ] Assert URL or title

```
cy.visit("https://example.cypress.io");
cy.url().should("include", "cypress");
```

### CHALLENGE:
- [ ] Add a 5th test: `performance_glitch_user` should eventually succeed (it's just slow)
- [ ] Add a test for the `problem_user` and check the product images are broken

### OUTPUT:
- [ ] 4+ login tests passing

---

## WEEK 2, DAY 4 – Screenshots + Tracing (Debugging Tools)

### LEARN:
- [ ] Screenshots
  👉 https://playwright.dev/docs/screenshots
- [ ] Trace Viewer (Playwright's best debugging tool)
  👉 https://playwright.dev/docs/trace-viewer

### DO:
```typescript
// tests/tracing-demo.spec.ts
import { test, expect } from '@playwright/test';

test('take screenshot on demand', async ({ page }) => {
  await page.goto('https://www.saucedemo.com');
  await page.screenshot({ path: 'screenshots/login-page.png', fullPage: true });
  console.log('Screenshot saved!');
});
```

### Enable Tracing (in playwright.config.ts):
```typescript
use: {
  trace: 'on-first-retry',  // records trace only when a test fails and retries
  screenshot: 'only-on-failure',
  video: 'on-first-retry',
}
```

### EXERCISE:
- [ ] Intentionally break a test (wrong URL)
- [ ] Run it — observe the failure
- [ ] Run `npx playwright show-report` and view the trace
- [ ] Step through the trace and find where it failed

### OUTPUT:
- [ ] Screenshots working
- [ ] Trace viewer explored

---

## WEEK 2, DAY 5 – Test Hooks + Grouping

### LEARN:
- [ ] `beforeEach`, `afterEach`, `beforeAll`, `afterAll`
  👉 https://playwright.dev/docs/test-fixtures#auto-fixtures

### EXERCISES:
```typescript
// tests/hooks.spec.ts
import { test, expect } from '@playwright/test';

test.describe('Login tests with hooks', () => {

  test.beforeEach(async ({ page }) => {
    // Runs before every test in this describe block
    await page.goto('https://www.saucedemo.com');
  });

  test.afterEach(async ({ page }, testInfo) => {
    // Take screenshot if test failed
    if (testInfo.status !== testInfo.expectedStatus) {
      await page.screenshot({
        path: `screenshots/failed-${testInfo.title.replace(/\s/g, '-')}.png`
      });
    }
  });

  test('valid login works', async ({ page }) => {
    // No need to navigate — beforeEach handles it
    await page.getByTestId('username').fill('standard_user');
    await page.getByTestId('password').fill('secret_sauce');
    await page.getByTestId('login-button').click();
    await expect(page).toHaveURL(/inventory/);
  });

  test('invalid login shows error', async ({ page }) => {
    await page.getByTestId('username').fill('invalid_user');
    await page.getByTestId('password').fill('invalid_pass');
    await page.getByTestId('login-button').click();
    await expect(page.locator('[data-test="error"]')).toBeVisible();
  });

});
```

### CHALLENGE:
- [ ] Add `beforeAll` to log "Starting login test suite"
- [ ] Add `afterAll` to log "Login test suite finished"
- [ ] Observe the execution order in the terminal

---

## WEEK 2, DAY 6 – Data-Driven Testing

### LEARN:
- [ ] Parameterized tests with `test.each` (or array iteration)
  👉 https://playwright.dev/docs/test-parameterize

### EXERCISES:
```typescript
// tests/data-driven.spec.ts
import { test, expect } from '@playwright/test';

// Test data — an array of test cases
const loginTestCases = [
  {
    description:    'standard user can login',
    username:       'standard_user',
    password:       'secret_sauce',
    expectedURL:    /inventory/,
    expectedError:  null,
  },
  {
    description:    'locked out user cannot login',
    username:       'locked_out_user',
    password:       'secret_sauce',
    expectedURL:    null,
    expectedError:  'locked out',
  },
  {
    description:    'invalid credentials shows error',
    username:       'invalid_user',
    password:       'invalid_pass',
    expectedURL:    null,
    expectedError:  'Epic sadface',
  },
];

for (const testCase of loginTestCases) {
  test(testCase.description, async ({ page }) => {
    await page.goto('https://www.saucedemo.com');
    await page.getByTestId('username').fill(testCase.username);
    await page.getByTestId('password').fill(testCase.password);
    await page.getByTestId('login-button').click();

    if (testCase.expectedURL) {
      await expect(page).toHaveURL(testCase.expectedURL);
    }

    if (testCase.expectedError) {
      await expect(page.locator('[data-test="error"]'))
        .toContainText(testCase.expectedError);
    }
  });
}
```

### CHALLENGE:
- [ ] Add 2 more test cases to the array (problem_user, performance_glitch_user)
- [ ] Move the test data to a separate file `test-data/login-users.ts` and import it

---

## WEEK 2, DAY 7 – Week 2 Review + Refactor

### DO:
- [ ] Run all tests: `npx playwright test`
- [ ] Fix any failing tests
- [ ] Refactor: remove code duplication
- [ ] View the HTML report: `npx playwright show-report`
- [ ] Ensure all tests are committed to GitHub

### SELF-CHECK:
- [ ] Can I explain what a Playwright locator is?
- [ ] Can I write a test that fills a form and asserts on a result?
- [ ] Can I use `beforeEach` to avoid duplication?
- [ ] Can I read a Playwright error message?

---

## WEEK 3: Playwright — Forms, Navigation, and Waits
![Week 3](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week3.json)

---

## WEEK 3, DAY 1 – Waiting Strategies (CRITICAL)

### LEARN:
- [ ] Good vs bad selectors

✅ Use:

data-test attributes

❌ Avoid:

CSS classes
XPath (if unstable)

### DO:
```typescript
// tests/fixtures/users.ts
export const testUsers = {
  standard: { username: 'standard_user',      password: 'secret_sauce' },
  locked:   { username: 'locked_out_user',    password: 'secret_sauce' },
  problem:  { username: 'problem_user',       password: 'secret_sauce' },
  glitch:   { username: 'performance_glitch_user', password: 'secret_sauce' },
};

export const checkoutData = {
  firstName:  'Cedric',
  lastName:   'Magno',
  postalCode: '1100',
};
```

```typescript
// tests/fixtures/base-fixtures.ts
import { test as base, expect } from '@playwright/test';

type Fixtures = { loggedInPage: any };

export const test = base.extend<Fixtures>({
  loggedInPage: async ({ page }, use) => {
    await page.goto('https://www.saucedemo.com');
    await page.getByTestId('username').fill('standard_user');
    await page.getByTestId('password').fill('secret_sauce');
    await page.getByTestId('login-button').click();
    await expect(page).toHaveURL(/inventory/);
    await use(page); // test runs here
    // cleanup could go here
  },
});

export { expect };
```

```typescript
// tests/with-fixtures.spec.ts
import { test, expect } from './fixtures/base-fixtures';

test('already logged in — can add to cart', async ({ loggedInPage: page }) => {
  await page.locator('[data-test="add-to-cart-sauce-labs-backpack"]').click();
  await expect(page.locator('.shopping_cart_badge')).toHaveText('1');
});
```

---

## WEEK 3, DAY 4 – Page Object Model (POM)

### LEARN:
- [ ] What is Page Object Model?
  👉 https://playwright.dev/docs/pom
  👉 https://www.selenium.dev/documentation/test_practices/encouraged/page_object_models/

### WHY POM:
> Without POM: selector changes break every test that uses it.
> With POM: selector changes happen in ONE place only.

### DO:
```
tests/
├── pages/
│   ├── LoginPage.ts
│   ├── InventoryPage.ts
│   └── CartPage.ts
├── fixtures/
│   └── users.ts
└── e2e/
    └── checkout-flow.spec.ts
```

```typescript
// tests/pages/LoginPage.ts
import { Page, expect } from '@playwright/test';

export class LoginPage {
  constructor(private page: Page) {}

  async goto() {
    await this.page.goto('https://www.saucedemo.com');
  }

  async login(username: string, password: string) {
    await this.page.getByTestId('username').fill(username);
    await this.page.getByTestId('password').fill(password);
    await this.page.getByTestId('login-button').click();
  }

  async getErrorMessage(): Promise<string> {
    return await this.page.locator('[data-test="error"]').textContent() ?? '';
  }

  async expectError(text: string) {
    await expect(this.page.locator('[data-test="error"]')).toContainText(text);
  }
}
```

```typescript
// tests/pages/InventoryPage.ts
import { Page, expect } from '@playwright/test';

export class InventoryPage {
  constructor(private page: Page) {}

  async addItemToCart(itemName: string) {
    const slug = itemName.toLowerCase().replace(/ /g, '-');
    await this.page.locator(`[data-test="add-to-cart-${slug}"]`).click();
  }

  async getCartItemCount(): Promise<string> {
    return await this.page.locator('.shopping_cart_badge').textContent() ?? '0';
  }

  async goToCart() {
    await this.page.locator('.shopping_cart_link').click();
  }
}
```

```typescript
// tests/e2e/login-pom.spec.ts
import { test, expect } from '@playwright/test';
import { LoginPage } from '../pages/LoginPage';
import { InventoryPage } from '../pages/InventoryPage';

test.describe('Login using POM', () => {
  test('valid login', async ({ page }) => {
    const loginPage = new LoginPage(page);
    await loginPage.goto();
    await loginPage.login('standard_user', 'secret_sauce');
    await expect(page).toHaveURL(/inventory/);
  });

  test('invalid login shows error', async ({ page }) => {
    const loginPage = new LoginPage(page);
    await loginPage.goto();
    await loginPage.login('wrong_user', 'wrong_pass');
    await loginPage.expectError('Epic sadface');
  });
});
```

### CHALLENGE:
- [ ] Create a `CartPage.ts` page object
- [ ] Create a `CheckoutPage.ts` page object
- [ ] Refactor the full purchase flow test from Day 2 to use all 4 page objects

---

## WEEK 3, DAY 5 – Multi-Tab + Alerts + Dropdowns

### EXERCISES:
```typescript
// tests/interactions.spec.ts
import { test, expect } from '@playwright/test';

test('handle dropdown/select', async ({ page }) => {
  await page.goto('https://www.saucedemo.com');
  // Login first
  await page.getByTestId('username').fill('standard_user');
  await page.getByTestId('password').fill('secret_sauce');
  await page.getByTestId('login-button').click();

  // Sort products (dropdown)
  await page.locator('[data-test="product-sort-container"]').selectOption('za');
  const firstItem = await page.locator('.inventory_item_name').first().textContent();
  console.log('First item after Z-A sort:', firstItem);
});

test('handle browser alert', async ({ page }) => {
  // Go to a page with an alert
  page.on('dialog', async dialog => {
    console.log('Dialog message:', dialog.message());
    await dialog.accept(); // or dialog.dismiss()
  });

  await page.goto('https://the-internet.herokuapp.com/javascript_alerts');
  await page.getByRole('button', { name: 'Click for JS Alert' }).click();
});
```

---

## WEEK 3, DAYS 6–7 – Review + Refactor

### CHECKLIST:
- [ ] All tests use Page Object Model
- [ ] Test data is in fixtures files, not hardcoded in tests
- [ ] No `waitForTimeout()` anywhere
- [ ] All tests pass: `npx playwright test`
- [ ] HTML report looks clean
- [ ] Everything pushed to GitHub

---

## WEEK 4: Playwright — Cross-Browser + Advanced Selectors
![Week 4](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week4.json)

---

## WEEK 4, DAYS 1–2 – Cross-Browser Testing

### LEARN:
- [ ] Playwright browser configuration
  👉 https://playwright.dev/docs/browsers

### DO:
```typescript
// playwright.config.ts — enable multiple browsers
projects: [
  { name: 'chromium', use: { ...devices['Desktop Chrome']  } },
  { name: 'firefox',  use: { ...devices['Desktop Firefox'] } },
  { name: 'webkit',   use: { ...devices['Desktop Safari']  } },
  // Mobile
  { name: 'Mobile Chrome',  use: { ...devices['Pixel 5']       } },
  { name: 'Mobile Safari',  use: { ...devices['iPhone 13']     } },
],
```

```bash
npx playwright test --project=firefox       # run in Firefox only
npx playwright test --project=webkit        # run in Safari only
npx playwright test --project="Mobile Chrome" # mobile
```

### EXERCISE:
- [ ] Run your login tests across all 3 browsers
- [ ] Fix any browser-specific failures you find
- [ ] Run in mobile viewport and check if tests still pass

---

## WEEK 4, DAYS 3–5 – Network Interception + Mocking

### LEARN:
- [ ] Intercept network requests
  👉 https://playwright.dev/docs/network

### EXERCISES:
```typescript
// tests/network.spec.ts
import { test, expect } from '@playwright/test';

test('intercept and inspect API calls', async ({ page }) => {
  // Capture all network requests
  const requests: string[] = [];
  page.on('request', req => requests.push(req.url()));

  await page.goto('https://www.saucedemo.com');
  console.log('Requests made:', requests);
});

test('mock an API response', async ({ page }) => {
  // Intercept API call and return fake data
  await page.route('**/api/products', async route => {
    await route.fulfill({
      status: 200,
      contentType: 'application/json',
      body: JSON.stringify([{ id: 1, name: 'Mocked Product', price: 9.99 }]),
    });
  });

  await page.goto('https://your-app.com/products');
  // Now the app receives your mocked data
});

test('simulate 500 server error', async ({ page }) => {
  await page.route('**/api/login', route => {
    route.fulfill({ status: 500, body: 'Server Error' });
  });

  await page.goto('https://your-app.com');
  // Test how your app handles server errors
});
```

---

## WEEK 4, DAYS 6–7 – Review + Week 2-4 Recap

### FINAL CHECKLIST FOR WEEKS 2–4:
- [ ] `tests/pages/` has at least 3 page objects
- [ ] `tests/fixtures/` has test data
- [ ] Tests run cross-browser
- [ ] No hardcoded waits, no magic strings
- [ ] HTML reports clean
- [ ] Pushed to GitHub with meaningful commit messages

---

# 🔵 WEEK 5–6: TypeScript + Framework Design
![Week 5-6](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week5-6.json)

---

## WEEK 5: TypeScript for Playwright
![Week 5](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week5.json)

📚 Resources: [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook)

### WHY TYPESCRIPT:
- Catch bugs before running tests
- Autocomplete in VS Code (intellisense)
- Required for most professional Playwright projects

---

## WEEK 5, DAYS 1–2 – Types + Interfaces

### LEARN:
- [ ] Basic types
  👉 https://www.typescriptlang.org/docs/handbook/2/everyday-types.html
- [ ] Interfaces
  👉 https://www.typescriptlang.org/docs/handbook/2/objects.html

### EXERCISES:
```typescript
// types/test-types.ts

// Basic types
const username: string  = "admin";
const attempts: number  = 0;
const isLoggedIn: boolean = false;
const roles: string[]   = ["admin", "user", "manager"];

// Interface
interface User {
  username: string;
  password: string;
  role:     "admin" | "user" | "manager";  // union type
  active:   boolean;
  loginCount?: number;  // optional
}

// Type-safe user objects
const testUsers: User[] = [
  { username: "admin",    password: "admin123",  role: "admin", active: true  },
  { username: "standard", password: "pass123",   role: "user",  active: true  },
  { username: "locked",   password: "pass123",   role: "user",  active: false },
];

// Type-safe function
function getActiveUsers(users: User[]): User[] {
  return users.filter(user => user.active);
}

// Type-safe return
function getUser(username: string): User | undefined {
  return testUsers.find(u => u.username === username);
}
```

---

## WEEK 5, DAYS 3–4 – Type Functions + Generics

### EXERCISES:
```typescript
// Function with typed parameters and return
async function login(
  page: Page,
  username: string,
  password: string
): Promise<boolean> {
  await page.goto('https://www.saucedemo.com');
  await page.getByTestId('username').fill(username);
  await page.getByTestId('password').fill(password);
  await page.getByTestId('login-button').click();

  try {
    await page.waitForURL(/inventory/, { timeout: 3000 });
    return true;
  } catch {
    return false;
  }
}

// Generic function
function getFirst<T>(items: T[]): T | undefined {
  return items[0];
}

const firstUser = getFirst<User>(testUsers);
```

---

## WEEK 5, DAYS 5–6 – Convert Test Files to TypeScript

### DO:
- [ ] Ensure all `.js` files are `.ts` files (Playwright creates `.ts` by default)
- [ ] Add types to all page object methods
- [ ] Add types to all fixture objects

### EXERCISE — Typed Page Object:
```typescript
// pages/LoginPage.ts (fully typed)
import { Page, Locator, expect } from '@playwright/test';

interface LoginCredentials {
  username: string;
  password: string;
}

export class LoginPage {
  private readonly usernameInput: Locator;
  private readonly passwordInput: Locator;
  private readonly loginButton:   Locator;
  private readonly errorMessage:  Locator;

  constructor(private page: Page) {
    this.usernameInput = page.getByTestId('username');
    this.passwordInput = page.getByTestId('password');
    this.loginButton   = page.getByTestId('login-button');
    this.errorMessage  = page.locator('[data-test="error"]');
  }

  async goto(): Promise<void> {
    await this.page.goto('https://www.saucedemo.com');
  }

  async login(credentials: LoginCredentials): Promise<void> {
    await this.usernameInput.fill(credentials.username);
    await this.passwordInput.fill(credentials.password);
    await this.loginButton.click();
  }

  async getErrorText(): Promise<string> {
    return await this.errorMessage.textContent() ?? '';
  }

  async expectSuccessfulLogin(): Promise<void> {
    await expect(this.page).toHaveURL(/inventory/);
  }

  async expectErrorContaining(text: string): Promise<void> {
    await expect(this.errorMessage).toContainText(text);
  }
}
```

---

# 🔵 WEEK 3: Cypress Advanced
![Week 3](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week3.json)

## 📅 DAY 1 - Fixtures
- [ ] Create JSON test data
- [ ] Use cy.fixture()

```
cy.fixture("users.json").then(data => {
  cy.log(data);
});
```

### OUTPUT:
- [ ] External test data used

## 📅 DAY 2 - Custom Commands
- [ ] Create cy.login()

```
Cypress.Commands.add("login", (username, password) => {
  cy.get('[data-test="username"]').type(username);
  cy.get('[data-test="password"]').type(password);
});
```

### OUTPUT:
- [ ] Reusable command

## 📅 DAY 3 - API Testing
Use:
https://jsonplaceholder.typicode.com
- [ ] cy.request GET

```
cy.request("GET", "/posts").its("status").should("eq", 200);
```

### OUTPUT:
- [ ] API test

## 📅 DAY 4 - POST Request
- [ ] Send POST request
- [ ] Validate response
```
cy.request("POST", "/posts", {
  title: "test"
}).its("status").should("eq", 201);
```

### OUTPUT:
- [ ] API validation test

## 📅 DAY 5 - Hooks
- [ ] beforeEach setup
```
beforeEach(() => {
  cy.visit("/");
});
```

---

## WEEK 8, DAYS 6–7 – Week 7–8 Final Review

### FINAL CHECKLIST:
- [ ] API tests: GET, POST, PUT, DELETE all covered
- [ ] Auth state setup working
- [ ] Tests run in parallel
- [ ] Retries configured
- [ ] Visual snapshots created
- [ ] Accessibility tests added
- [ ] All pushed to GitHub

---

# 🔴 WEEK 9: CI/CD + GitHub Actions
![Week 9](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week9.json)

📚 Resources:
- [GitHub Actions Docs](https://docs.github.com/en/actions)
- [Playwright CI Guide](https://playwright.dev/docs/ci-github-actions)

---

## WEEK 9, DAY 1 – What is CI/CD?

### LEARN:
- [ ] What is CI/CD?
  👉 https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions
- [ ] Why run tests in the pipeline?
  👉 https://martinfowler.com/articles/continuousIntegration.html

### KEY CONCEPT:
> CI/CD means: every time you push code to GitHub, your tests run automatically.
> If tests fail, the push is blocked. This prevents broken code from going to production.

---

## WEEK 9, DAYS 2–3 – Create Your First Pipeline

### DO:
```yaml
# .github/workflows/playwright.yml
name: Playwright Tests

on:
  push:
    branches: [ main, develop ]
  pull_request:
    branches: [ main ]

jobs:
  test:
    timeout-minutes: 60
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v4

      - name: Setup Node.js
        uses: actions/setup-node@v4
        with:
          node-version: '20'
          cache: 'npm'

      - name: Install dependencies
        run: npm ci

      - name: Install Playwright browsers
        run: npx playwright install --with-deps

      - name: Run Playwright tests
        run: npx playwright test

      - name: Upload HTML report
        uses: actions/upload-artifact@v4
        if: always()   # upload even if tests fail
        with:
          name: playwright-report
          path: playwright-report/
          retention-days: 30
```

### EXERCISE:
- [ ] Create this file in your repo
- [ ] Push to GitHub
- [ ] Go to GitHub → Actions tab — watch tests run
- [ ] Break a test intentionally and push — see the pipeline fail
- [ ] Fix it and push again — see it pass

---

## WEEK 9, DAYS 4–5 – Advanced Pipeline Configuration

### ADVANCED YAML:
```yaml
# Run tests in parallel across multiple OS
strategy:
  matrix:
    os: [ubuntu-latest, windows-latest]
    browser: [chromium, firefox, webkit]

# Run only specific tests in CI
- name: Run smoke tests
  run: npx playwright test --grep @smoke

# Different commands per environment
- name: Run tests
  run: npx playwright test
  env:
    BASE_URL: ${{ secrets.STAGING_URL }}
    TEST_USERNAME: ${{ secrets.TEST_USERNAME }}
    TEST_PASSWORD: ${{ secrets.TEST_PASSWORD }}
```

### DO:
- [ ] Add `@smoke` tag to your most critical tests
- [ ] Create a separate smoke-tests pipeline that runs on every push
- [ ] Store test credentials as GitHub Secrets (not hardcoded!)

---

# 🔁 WEEK 4-5: TypeScript Transition
![Week 4-5](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week4-5.json)

📚 Use:
- TypeScript Documentation

Why TypeScript?
- Prevent bugs early
- Better IDE support

Start SMALL:
- Only add types to variables first
- Don’t convert everything at once

## 📅 KEY DAILY PATTERN

### Day 1-2:
- [ ] Add types to variables

### Day 3-4:
- [ ] Type functions

### Day 5-6:
- [ ] Convert Cypress tests to TS

### Day 7:
- [ ] Fix errors + review

---

# 🟡 WEEK 6: Framework Design
![Week 6](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week6.json)

Learn:
- [ ] What is Page Object Model (POM)?
- [ ] Why separate selectors?

DO:
- [ ] Create folder structure:
  /pages
  /tests
  /fixtures

- [ ] Create LoginPage.js:
  methods:
    - [ ] visit()
    - [ ] login(username, password)

Exercise:
- Refactor login test to use LoginPage
- [ ] Create Page Objects
- [ ] Move selectors out of tests
- [ ] Separate test data
- [ ] Clean folder structure

```
class LoginPage {
  visit()                  { cy.visit('https://www.saucedemo.com'); }
  typeUsername(username)   { cy.get('[data-test="username"]').type(username); }
  typePassword(password)   { cy.get('[data-test="password"]').type(password); }
  clickLogin()             { cy.get('[data-test="login-button"]').click(); }
  login(username, password) {
    this.typeUsername(username);
    this.typePassword(password);
    this.clickLogin();
  }
}
export default new LoginPage();
```

### WEEK 12, DAYS 5–7 – Cypress CI/CD

```yaml
# .github/workflows/cypress.yml
name: Cypress Tests
on: [push]
jobs:
  cypress-run:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: cypress-io/github-action@v6
        with:
          command: npx cypress run
```

### CYPRESS vs PLAYWRIGHT — KEY DIFFERENCES TO REMEMBER:
| | Cypress | Playwright |
|---|---|---|
| Execution | Inside browser | Via DevTools Protocol |
| Multi-tab | ❌ | ✅ |
| Multi-browser | Limited Safari | Full cross-browser |
| Parallel | Paid | Free |
| Mobile | ❌ (viewport only) | ✅ |
| Auto-wait | Yes | Yes (better) |
| Time-travel debug | ✅ Excellent | ✅ Via Trace Viewer |

---

# ➕ SUPPLEMENTAL WEEK 13–14: Selenium (Enterprise/Legacy)

> **When to use Selenium:** When applying to large enterprise companies (banking, insurance, government, telco) that have existing Java-based test suites. Knowing Selenium significantly widens your job options.

📚 Resources: [Selenium Docs](https://www.selenium.dev/documentation/) · [Selenium with Java](https://www.selenium.dev/documentation/webdriver/)

---

## WEEK 13: Selenium + Java Basics
![Week 13](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week13.json)

📚 Use:
- Playwright
- GitHub Actions

Install

```
npm init playwright@latest
```

Learn:
- [ ] What is CI/CD?
CI/CD Sample:
```name: Run Tests

on: [push]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: npm install
      - run: npx cypress run
```

- [ ] Why run tests in pipeline?

DO:
- [ ] Create .github/workflows/test.yml
- [ ] Run Cypress tests on push

Exercise:
- [ ] Break a test and see pipeline fail

## 📅 KEY TASKS

- [ ] Install Playwright
- [ ] Write login test
- [ ] Convert Cypress tests
- [ ] Run multi-browser tests
- [ ] Setup CI/CD pipeline

---

# ➕ SUPPLEMENTAL WEEK 16: AI-Assisted Testing
![Week 16](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/cedric-magno/automation-training/main/.github/progress-week16.json)

> **Why this matters:** AI-augmented testing is growing fast. 70% of enterprises are expected to adopt AI testing by 2028. This is the direction the industry is heading.

---

## TOPICS TO EXPLORE:

### 1. Playwright Codegen (Built-in AI-like recording)
```bash
npx playwright codegen https://www.saucedemo.com
```
> Records your interactions and generates Playwright code automatically. Great for bootstrapping tests fast.

### 2. GitHub Copilot for Tests
- [ ] Enable Copilot in VS Code
- [ ] Write a comment: `// test that login fails with wrong password`
- [ ] Let Copilot suggest the test code
- [ ] Review, correct, and learn from the suggestion

### 3. Playwright MCP (AI-controlled browser)
- [ ] Learn about Playwright's Model Context Protocol integration
  👉 https://playwright.dev/docs/mcp
- [ ] Understand how AI agents can control browsers via Playwright

### 4. Self-Healing Tests
- [ ] Research tools like Healenium, Testim, or Mabl
  👉 https://healenium.io
- [ ] Understand the concept: tests that auto-fix broken selectors

### KEY SKILLS FOR AI-AUGMENTED TESTING:
- [ ] Writing clear, descriptive test names (AI uses these as context)
- [ ] Using semantic selectors (role, label, text) — AI generates these better
- [ ] Understanding what AI-generated tests get wrong (hallucinations)
- [ ] Reviewing and validating AI suggestions critically

---

# 🚀 NEXT STEPS + CAREER ROADMAP

## Immediate (After Week 10):
1. **Polish your GitHub portfolio**
   - Pin your automation-training repo
   - Write a great README with a CI/CD badge
   - Record a short screen demo of your tests running

2. **Build a portfolio project from scratch**
   - Pick any public site (OpenCart, Magento demo, DemoQA)
   - Write a full test suite with POM + API + CI/CD
   - Use TypeScript throughout

3. **Learn test reporting**
   - Allure Reports (most used in enterprise)
   - Playwright's built-in HTML reporter

## Medium-term (3–6 months):
4. **Add high-value skills** (appear in 60%+ of job postings):
   - Docker basics (run tests in containers)
   - SQL basics (validate data in databases)
   - Postman (API exploration)
   - JIRA (defect tracking)

5. **Certifications (optional but helpful):**
   - ISTQB Foundation Level
   - AWS/Azure basics (cloud CI/CD)

## Job Titles to Target:
| Title | Focus | Level |
|---|---|---|
| QA Automation Engineer | Playwright/Cypress | Junior–Mid |
| SDET | Full stack testing | Mid–Senior |
| QA Engineer (Automation) | UI + API | Junior |
| Test Automation Engineer | Framework design | Mid |

---

# ⚠️ COMMON MISTAKES

| Mistake | Why It's Bad | Fix |
|---|---|---|
| Using `waitForTimeout(3000)` | Hard waits = slow + fragile tests | Wait for specific element/URL/state |
| CSS class selectors (`.btn-login`) | Classes change often | Use `data-testid`, role, or label |
| XPath everywhere | Hard to read, brittle | Use Playwright locators |
| No POM (selectors in every test) | One UI change = 50 test updates | Use Page Object Model |
| Copy-pasting without understanding | You can't debug what you don't understand | Type code manually, read the docs |
| Not committing daily | Lose progress, no portfolio evidence | Push to GitHub every session |
| Ignoring TypeScript errors | Bugs caught too late | Fix all TS errors: `npx tsc --noEmit` |
| Hardcoding credentials in test files | Security risk, hard to maintain | Use env variables or secrets |

---

# 📋 INTERVIEW PREP CHEAT SHEET

**Questions you should be able to answer:**

### Framework Questions:
- Why did you choose Playwright over Cypress or Selenium?
- Explain how Playwright's auto-waiting works
- What is the Page Object Model and why do you use it?
- How do you handle flaky tests?

### Practical Questions:
- Walk me through your test framework structure
- How do you run tests in CI/CD?
- How do you test APIs with Playwright?
- How do you handle test data?

### Scenario Questions:
- A test that was passing is now failing. How do you investigate?
- Your team wants to add automation to a legacy app. What do you do?
- A developer says "why do we need tests, it slows us down?" — what do you say?

**Your answers should reference your actual GitHub projects.**

---

# 📊 FINAL NOTE

This plan was designed for hands-on learners. If you follow it:

- ✅ You'll write real code every day
- ✅ You'll build a production-quality framework
- ✅ You'll understand Playwright deeply — not just copy-paste
- ✅ You'll have GitHub proof of your skills
- ✅ You'll be ready for junior/mid SDET interviews

**The industry is moving fast. Playwright is the right bet for 2026.**

---

*Last updated: May 2026 | Based on 2026 job market data*
