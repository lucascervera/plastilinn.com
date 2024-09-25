## Quick start

[Try plastilinn](#try-plastilinn)
[Download the Plastilinn doc template](#download-the-plastilinn-doc-template)
[Load your Plastilinn doc](#load-your-plastilinn-doc)
[Open the idea definition guide](#open-the-idea-definition-guide)

- You don't need to install nothing in your computer, just download <a href="https://xbokmd.github.io/plastilinn/public/plastilinn.zip"  download="plastilinn.zip">Plastilinn zip</a> and unzip it in a directory of your choice (IE "C:\plastilinn")
- Haz una copia del documento llamado X. El nombre del fichero   Sustituyendo Project name por el nombre de tu proyecto. para que coincida con el tu proyecto. A partir de ahora nos referiremos a este fichero como tu plastilinn doc. (Por ejemplo, cambia el nombre de. "Plastilinn_doc_project_name.md" a "Plastilinn_doc_tesla.md")
- Open the <a href="https://xbokmd.github.io/plastilinn/app.html" target="_blank">Plastilinn application and click on the "CHOOSE FILE" button</a>
- Navigate to your plastilinn folder (IE "C:\plastilinn") and load your plastilinn doc (or the sample doc "plastilinn_doc_SpaceX.md" if you just want to play around with an example completed document)
- Now you have a Plastilinn document loaded. Explore the different options the app offers.

<span id="create-a-new-business-from-scratch"></span>
##### Create a new business from scratch

<span id="improve-an-existing-business"></span>
##### Improve an existing business

<span id="download-the-Plastilinn-doc-template"></span>
##### Download the Plastilinn doc template

- Download the template from this link <a href="https://xbokmd.github.io/plastilinn/public/Plastilinn_doc_project_name.md" download="Plastilinn_doc_project_name.md">Plastilinn doc template</a>
- Save it in a folder called "Plastilinn"
- Rename the template using your project's name (IE, "Plastilinn_doc_SpaceX.md")

<span id="load-your-Plastilinn-doc"></span>
##### Load your Plastilinn doc

Load the Plastilinn doc template you just downloaded by clicking the "choose file" button in the <a href="https://xbokmd.github.io/plastilinn/app.html" target="_blank">Plastilinn application</a>.

<span id="open-the-idea-definition-guide"></span>
##### Open the idea definition guide

Click on the [Idea Definition Guide](#idea-definition-guide) guide and follow the instructions.

<a href="https://xbokmd.github.io/plastilinn/app.html" target="_blank">Open the plastilinn app online</a>

In Plastilinn, everything revolves around your Plastilinn doc, which is a single document containing your entire business model.

A business model is a simplified representation of the logic that makes a business profitable. That is, your business model is captured in your Plastilinn doc, which is a document that gathers all relevant information about your business. It includes information about who your customers are, what problems you help them solve, what channels you will use for them to get to know you, etc.

A Plastilinn doc is simply a plain text file in Markdown format.

<span id="features"></span>
### Features

[Features](#features)
[Plain Text](#plain-text)
[Markdown](#markdown)
[Local Storage](#local-storage)
[Structured Business Model](#structured-business-model)

<span id="markdown"></span>
### Markdown

Markdown is a lightweight markup language designed to be easy to write and read. It is characterized by its simplicity, allowing users to format text using a series of simple symbols and characters, such as asterisks for bold and underscores for italic, among others. The great advantage of Markdown is that it allows you to focus on the content of the text without distractions, making it easy to create well-structured and readable documents both in their raw form and in their final version, once converted to HTML or other formats. This makes it especially popular for writing technical documentation, README files in software projects, and for content creators on blogging platforms and content management systems seeking an efficient and accessible way to write.

A Markdown is document is really a plain text file. These are the simplest files and can be edited with any text editor. All operating systems (Windows, Mac, Linux, etc...) come with a default plain text editor (for example, Notepad on Windows), so by using this file format, you ensure it is always editable regardless of the operating system or environment used by the user.

<span id="local-storage"></span>
### Local Storage

Your document is saved on your hard drive like other documents you work with. Inside your "Plastilinn" folder on your hard drive, both the current version of your document and previous versions are stored. Other tools similar to Plastilinn operate with a software-as-a-service (SaaS) model, where your information is stored in a cloud database and controlled by the service provider. This means you are tied to them, and you may lose access to the information you've created if they decide to increase prices, you want to stop paying for the service for any reason, or the service provider goes out of business.

<span id="structured-business-model"></span>
## Structured Business Model

A Plastilinn doc allows you to describe your business model in a structured manner. You could describe your business model simply by writing a narrative document (as if it were a novel) that outlines the logic through which your business makes money. However, in that format, you cannot leverage the information effectively. Instead, in Plastilinn, your business model is described using a predefined structure, which uses the following components:

<span id="section"></span>
| Type | Examples: 🆔Element, 📖description and (example of Space X)|
|------------|-------------------------------------------------------|
| **Section** Content units that describe specific aspects of the business model. | **Mission:** Fundamental purpose of the organization ("Make human life multi-planetary")<br>**Profile Satellite Launch Customers - Goals:** Problems, needs, or desires of the relevant stakeholders for the business. (Reduce launch costs, Increase launch reliability, Expand global satellite internet coverage.)<br>**Revenue Lines:** Sources of income generated by the business. (Commercial launches, Contracts with government agencies, Starlink internet services.)|
| **Class** Elements representing key concepts or components within the business model. | **Key:** Critical elements for success. (Reusable rocket technology)<br>**Solution:** Offered solutions. (Starship for Mars missions)<br>**Offering:** Value proposition. (Launch services for satellites and payloads into space) |
| **Marker** Indicators or notes that help evaluate, classify, or prioritize components of the business model. | **Weight:** Importance of components. (Reusable rocket technology has a weight of "*****")<br>**Priority:** Urgency of development. (Starship development has a priority of "!!!!!")<br>**Certainty:** Reliability of the component. (Feasibility of reusable rockets is marked with "=")|

[Plastilinn documentation](https://xbokmd.github.io/plastilinn/index.html#/)

<span id="editing-your-plastilinn-doc"></span>
## Editing Your Plastilinn Doc

[Editing Your Plastilinn Doc](#editing-your-plastilinn-doc)
[Document block editor](#document-block-editor)
[Using Markers](#using-markers)
[Export Content](#export-content)

You can edit your Plastilinn doc directly in the application <a href="https://stackedit.io/app#" target="_blank">Stackedit</a>

<span id="document-block-editor"></span>
### Document block editor
Any line starting with a "#" symbol is considered a block start, wheter it is a Markdown heading or a tag.

<span id="using-markers"></span>
### Using Markers

| marker | low | high |
| --- | --- | --- |
| weight | <span data-tag='*'>*</span><kbd class='kbd kbd-xs'>#*</kbd> | <kbd class='kbd kbd-xs'>#*****</kbd> <span data-tag='*****'>*****</span> |
| completion | <span data-tag='>'>></span><kbd class='kbd kbd-xs'>#></kbd> | <kbd class='kbd kbd-xs'>#>>>>></kbd> <span data-tag='>>>>>'>>>>>></span> |
| priority | <span data-tag='!'>!</span><kbd class='kbd kbd-xs'>#!</kbd> | <kbd class='kbd kbd-xs'>#!!!!!</kbd> <span data-tag='!!!!!'>!!!!!</span> |
| uncertainty | <span data-tag='?'>?</span><kbd class='kbd kbd-xs'>#?</kbd> | <kbd class='kbd kbd-xs'>#?????</kbd> <span data-tag='?????'>?????</span> |
| risk | <span data-tag='¡'>¡</span><kbd class='kbd kbd-xs'>#¡</kbd> | <kbd class='kbd kbd-xs'>#¡¡¡¡¡</kbd> <span data-tag='¡¡¡¡¡'>¡¡¡¡¡</span> |
| validation | <span data-tag='='>=</span><kbd class='kbd kbd-xs'>#=</kbd> | <kbd class='kbd kbd-xs'>#=====</kbd> <span data-tag='====='>=====</span> |

<span id="export-content"></span>
### Export Content

At any time, you can export your document as HTML by clicking the "export" button in the upper right corner. Your document will be exported as clean HTML that you can open, import, or copy and paste into your favorite document editor (MS Word, Google Docs, etc.). The following <a href="https://drive.google.com/drive/folders/1IbMu1j6hqWG0BLllePYftHpzubjxCEQy?usp=sharing" target="_blank">link opens a Google Drive folder where you can view a sample of all these documents</a>.

<span id="xbok"></span>
### xBoK

The metamodel describes the structure and essential elements that should be considered when designing and analyzing business models. This structure includes components such as "key", "organization", "journey", "assumption", "solution", "offering", and many more, each with its own symbol, color, and detailed definition. These elements cover a wide range of critical aspects of a business, from key resources and activities to value propositions, customer segments, and relationships with them.