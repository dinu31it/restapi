# 📦 Pull Request Template

## ✅ PR Checklist

Please check all that apply:

- [ ] My code follows the existing style and conventions
- [ ] I have added or updated unit tests
- [ ] I have updated relevant documentation (README, OpenAPI spec, etc.)
- [ ] The build passes locally (`./mvnw clean install` or `./gradlew build`)
- [ ] This PR only affects one microservice (single responsibility)
- [ ] I have verified integration with dependent services (if applicable)

---

## 🧾 Description

<!--
Clearly describe the purpose of the PR.
What feature/bugfix/enhancement does it address?
Which Jira/Trello ticket or issue does it relate to?
-->

Fixes: #[Issue Number] (or N/A)

---

## 📂 Type of Change

Please mark the relevant options:

- [ ] ✨ Feature
- [ ] 🐛 Bugfix
- [ ] ♻️ Refactor
- [ ] 🧪 Test-related change
- [ ] 📝 Documentation update
- [ ] 🔧 Build/CI/CD
- [ ] ⚙️ Config changes

---

## 🔄 Microservice Impact

- **Affected microservice**: `restapi`
- **New endpoints introduced** (if any):
  ```http
  POST /api/v1/resource
  GET /api/v1/resource/{id}