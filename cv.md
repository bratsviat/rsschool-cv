# Sviat Brat

# My Contact Info

* **Address:** Minsk, Belarus
* **Phone:** +375 17 123 45 67
* **Email:** [attempt2learnjs@email.com](mailto:attempt2learnjs@email.com)
* **GiHub:** [bratsviat](https://github.com/bratsviat)

# Summary

QA professional with nearly 6 years of experience across manual and automation testing, recently transitioned into a Product Owner role. I thrive in cross-functional teams and love building efficient, quality-focused solutions. I enjoy translating complex requirements into actionable plans, whether it’s for test automation or product delivery. Strong believer in continuous learning and owning both code and product.

# Skills

* **Testing:** Manual, Functional, Regression, API
* **Automation:** JavaScript, WebdriverIO, Cypress, Postman, BRUNO
* **CI/CD:** Git, GitHub Actions, Jenkins, Docker
* **Product Ownership:** Backlog Management, Roadmapping, Agile/Scrum, Stakeholder Communication
* **Collaboration:** Jira, Confluence, Figma, Slack, Mural
* **Tech Stack:** JavaScript, TypeScript (basic), SQL, REST APIs (basic)
* **Dev Tools:** Linux, Windows, VS Code, Postman, BRUNO

# Code examples

```
// Basic example of WebdriverIO + Mocha test
describe('Login Page', () => {
    it('should allow user to log in with valid credentials', async () => {
        await browser.url('/login');
        await $('#username').setValue('testuser');
        await $('#password').setValue('securePass123');
        await $('button[type="submit"]').click();
        await expect($('.dashboard')).toBeDisplayed();
    });
});
```
