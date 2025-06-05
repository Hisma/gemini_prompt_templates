# Gemini Prompt Templates

This repository contains a collection of prompt templates for Gemini, organized by roles and use cases. These templates are designed to help you get the most out of Gemini across Google Workspace applications.

## Origin

These templates are derived from the official "Gemini for Google Workspace Prompting Guide 101" document. The guide provides comprehensive instructions and examples for effectively using Gemini in various Google Workspace applications. This repository organizes those templates into a more modular and accessible format for easy reference and implementation.

## Repository Structure

```
gemini_prompt_templates/
├── README.md                  # Project overview and usage instructions
├── gemini-for-google-workspace-prompting-guide-101.md  # Original source document
│
├── core/                      # Core templates and principles
│   ├── base_template.md       # Base template structure
│   └── prompting_principles.md # General principles for effective prompting
│
├── roles/                     # Role-specific templates
│   ├── administrative_support/ # Templates for administrative professionals
│   ├── marketing/             # Templates for marketing professionals
│   └── sales/                 # Templates for sales professionals
│
└── use_cases/                 # Use case-specific templates
    ├── email_communication/   # Templates for email drafting and management
    ├── meeting_management/    # Templates for meeting preparation and follow-up
    └── content_creation/      # Templates for creating various types of content
```

## How to Use These Templates

1. **Browse by Role or Use Case**: Find templates that match your professional role or specific task you're trying to accomplish.

2. **Customize the Template**: Replace the placeholders (indicated by [BRACKETS]) with your specific information.

3. **Use in the Appropriate Google Workspace Application**: Each template indicates which Gemini integration it works best with (e.g., Gemini in Gmail, Gemini in Docs, Gemini Advanced).

4. **Iterate as Needed**: If the initial results aren't exactly what you need, refine your prompt or try a different template.

## Template Format

Each template follows a consistent format:

```
### Template Name (Gemini Application)

[CLEAR INSTRUCTION]

[CONTEXT/BACKGROUND INFORMATION]

[SPECIFIC REQUIREMENTS]

[OPTIONAL: FORMAT INSTRUCTIONS]
```

**Example:**
```
### Customer Follow-up Email (Gemini in Gmail)

Draft a follow-up email to [CUSTOMER NAME] regarding our discussion about [PRODUCT/SERVICE].

We met on [DATE] and discussed [KEY POINTS]. They expressed interest in [SPECIFIC FEATURES/BENEFITS].

Include information about [PRICING/TIMELINE/NEXT STEPS] and suggest [PROPOSED ACTION].

Format the email with a professional greeting, 2-3 concise paragraphs, and a clear call to action.
```

Templates use [BRACKETS] to indicate placeholders that you should replace with your specific information. Each template also specifies which Gemini application it works best with (e.g., Gemini in Gmail, Gemini in Docs, Gemini Advanced).

## Best Practices

For general guidance on crafting effective prompts for Gemini, refer to the [prompting_principles.md](./core/prompting_principles.md) file in the core directory.

## How to Access and Use Gemini for Google Workspace

To put these templates to use, you'll need access to Gemini for Google Workspace:

### Subscription Requirements
- Gemini for Google Workspace requires a Google Workspace subscription
- Depending on your organization, you may need a specific Gemini Education or Gemini Education Premium license assigned to your account
- Business and Enterprise Google Workspace plans now include access to the Gemini app, NotebookLM, and Gemini in Gmail, Docs, Meet, and more

### Accessing Gemini in Workspace Apps
1. **In Gmail, Docs, Sheets, and Slides**: Look for the Gemini icon in the side panel on the right side of your screen
2. **In Meet**: Use the "Take notes with Gemini" feature during meetings
3. **Standalone Gemini app**: Access at [gemini.google.com](https://gemini.google.com) with enterprise-grade security

### Practical Usage Examples

#### Using Templates in Gmail
1. Open Gmail and compose a new email or reply to an existing one
2. Click the Gemini icon in the right sidebar to open the Gemini panel
3. Copy a template from this repository (e.g., from `use_cases/email_communication/templates.md`)
4. Paste the template into the Gemini prompt field
5. Replace the [PLACEHOLDERS] with your specific information
6. Click "Create" to generate the content
7. Review, edit as needed, and insert into your email

#### Using Templates in Google Docs
1. Open a Google Doc
2. Click the Gemini icon in the right sidebar
3. Copy a template from this repository (e.g., from `use_cases/content_creation/templates.md`)
4. Paste the template into the Gemini prompt field
5. Replace the [PLACEHOLDERS] with your specific information
6. Click "Insert" to add the generated content to your document
7. Edit and format as needed

#### Using Templates in Gemini Advanced
1. Go to [gemini.google.com](https://gemini.google.com)
2. Copy a template from this repository
3. Paste the template into the chat interface
4. Replace the [PLACEHOLDERS] with your specific information
5. Press Enter to generate a response
6. Continue the conversation to refine the output

### Customizing Templates for Your Needs
- Feel free to modify any template to better suit your specific requirements
- Save frequently used customized templates for future use
- Combine elements from different templates for more complex tasks
- Experiment with different phrasings to get the best results

Remember that your data is your data - it's not used to train Gemini models or for ads targeting, and you can delete or export your content at any time.
