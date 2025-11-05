# 📚 LRLibs

<div align="center">
  <h3>Community-driven Open Source Libraries for the Liferay DXP Ecosystem.</h3>
</div>

**LRLibs** is a collaborative effort by developers committed to simplifying and enhancing the development experience within the Liferay Digital Experience Platform (DXP). We focus on delivering high-quality, specialized, and reusable Java libraries, APIs, and utilities to address common challenges.

---

## 🎯 Our Mission

To foster a vibrant and productive development community by providing essential, independently maintained, and well-documented components that extend Liferay DXP functionality.

## 📦 Core Repositories & Focus Areas

Our components are grouped into logical, single-focus repositories for easier maintenance and consumption. Each repository is a multi-module Maven project where individual libraries are published separately to Maven Central under the `org.lrlibs` Group ID.

| Repository | Focus Area | Status | Key Modules |
| :--- | :--- | :--- | :--- |
| **[`java-security-commons`](https://github.com/lrlibs/java-security-commons)** | Security, OAuth2, Permissions, and Authentication Utilities. | In Development | OAuth Client, Permission Utilities, Header Signing |
| `java-api-clients` | (Planned) Utilities for external service integration and DXP API consumption. | Planning | SOAP/REST Clients, JSON Mapping Utilities |
| `dxp-theme-utils` | (Planned) Helpers and tools for theme development and frontend optimization. | Planning | Theme Build Tools, Static Asset Management |

---

## 🚀 Getting Started

All our artifacts are published to **Maven Central**.

### 1. Group ID (Maven/Gradle)

To use any library from the LRLibs organization, include the following Group ID in your dependency management:

```xml
<groupId>org.lrlibs</groupId>
```

### 2. Example Dependency (from java-security-commons)

To include a specific module, simply use its unique Artifact ID:
```xml
<dependency>
    <groupId>org.lrlibs</groupId>
    <artifactId>lrlibs-security-oauth-client</artifactId>
    <version>1.0.0-SNAPSHOT</version>
</dependency>
```

---

## 👋 Community & Contributions

LRLibs is built by the community, for the community. We welcome all contributions!

* **Reporting Bugs / Requesting Features:** Open an [Issue](https://github.com/lrlibs/java-security-commons/issues) in the respective repository.
* **Code Contributions:** Check the `CONTRIBUTING.md` file in the project you wish to modify for guidelines on Pull Requests.

> 📢 **Disclaimer:** *LRLibs is an independent, community-driven open source initiative and is not affiliated with or sponsored by Liferay, Inc.*

---

### ⚖️ License

All projects within the LRLibs organization are typically licensed under the permissive **[MIT License](https://opensource.org/licenses/MIT)** or **[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)**. Please check the `LICENSE.md` file in each repository for specific details.
