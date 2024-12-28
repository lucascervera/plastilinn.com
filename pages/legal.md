# Plastilinn Google Add-on Documentation

1. [Privacy Policy](#1-privacy-policy)  
2. [Terms of Service](#2-terms-of-service)  
3. [Justification of Requested Scopes (OAuth Consent Explanation)](#3-justification-of-requested-scopes-oauth-consent-explanation)  
4. [Support and Contact Information](#4-support-and-contact-information)

---

## 1. Privacy Policy

**Effective Date:** 2024-12-28

### Introduction
This add-on (“the Service”) is designed to extend Google Docs functionality by providing a custom sidebar and various document-editing features. We respect your privacy and are committed to protecting your personal information.

### Data Collection
- **User Data:** Our add-on does not collect or store any personally identifiable information.  
- **Document Content:** The Service may access document content (text, headings, tags) strictly to apply formatting or insert markers/tags. This content is processed in real time and **never** stored on external servers.  
- **Analytics:** We do not use third-party analytics or tracking at this time. If we introduce analytics in future updates, it will be clarified here and will only collect non-personal usage data.

### Data Usage
- **Document Processing:** Any data accessed from the active Google Doc is used solely to enable the add-on features (e.g., tag insertion, marker formatting).  
- **No Third-Party Sharing:** We do not share user or document data with any third parties.

### Data Retention
- **Temporary Data:** All data is processed in-memory within the execution context of Google Apps Script and is not persisted after the session ends.  
- **No External Storage:** We do not maintain separate databases or cloud storages to keep document-related data.  
- **Copy/Paste:** Part of the application's functionality involves copying content from the document to the clipboard and inviting the user to paste it into an external AI assistant separate from this add-on.

### User Rights
- **Access & Control:** Since we do not store personal data, there is no long-term record to request or delete.  
- **Consent:** By installing or using this add-on, you consent to our usage of the minimal scope required to provide its functionality.

### Changes to this Privacy Policy
We may update this policy to reflect changes in our practices or for other operational, legal, or regulatory reasons. Any changes will be effective upon posting an updated version within this repository or add-on landing page.

---

## 2. Terms of Service

**Introduction**  
These Terms of Service (“Terms”) govern your use of the add-on. By installing or using the add-on, you agree to these Terms.

### License and Use
- **License Grant:** We grant you a non-exclusive, non-transferable, revocable license to use the add-on solely within Google Docs.  
- **Prohibited Uses:** You agree not to misuse the add-on, reverse-engineer, or use it in a way that violates Google’s Terms of Service or applicable laws.

### Disclaimer of Warranties
- The add-on is provided “as is” without warranties or conditions of any kind, whether express or implied. We do not warrant that the functionality will be uninterrupted or error-free.

### Limitation of Liability
- To the maximum extent permitted by law, we shall not be liable for any special, incidental, indirect, or consequential damages arising out of or related to your use or inability to use the add-on.

### Termination
- We reserve the right to terminate or suspend your access to the add-on at any time if we believe you have violated these Terms.

### Governing Law
- Any disputes arising under these Terms will be governed by and construed in accordance with the laws of the jurisdiction in which we operate, without regard to its conflict-of-law provisions.

---

## 3. Justification of Requested Scopes (OAuth Consent Explanation)

Our add-on requests the following permissions to function properly:

1. **`https://www.googleapis.com/auth/documents.currentonly`**  
   - **Why it is needed:**  
     - We need to read and modify the content (paragraphs, headings, tags) of the currently open Google Doc to insert markers, apply formatting, and update sections.  
   - **How it is used:**  
     - The add-on only processes the content in real time. It does not store or share the content externally.  

2. **`https://www.googleapis.com/auth/script.external_request`**  
   - **Why it is needed:**  
     - Allows the add-on to make limited external requests, such as fetching configuration files (e.g., JSON-based metamodel) or loading resources (e.g., CSS libraries).  
   - **How it is used:**  
     - This add-on currently fetches a remote JSON file (metamodel) for advanced document-block handling. No user content is sent externally.

3. **`https://www.googleapis.com/auth/script.container.ui`**  
   - **Why it is needed:**  
     - Enables the custom sidebar and dialogs within the Google Docs UI.  
   - **How it is used:**  
     - We provide a custom interface (sidebar) to interact with markers, tags, and other tools.

These scopes are the minimum necessary to provide the functionality of the add-on. We do not request any additional scopes beyond these.

---

## 4. Support and Contact Information

- **Email:** [plastilinn@plastilinn.com](mailto:plastilinn@plastilinn.com)  
- **Issues Tracker:** [GitHub Issues](https://github.com/lucascervera/plastilinn.com/issues)  
- **Website (Policy & Documentation):** [https://plastilinn.com](https://plastilinn.com)  

If you have any questions or concerns regarding the add-on or any aspect of these documents, please feel free to reach out through any of the channels above.

---

**Last Updated:** 2024-12-28
