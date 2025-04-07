# Sparky AI (CKEDITOR)

This simple recipe installs the base AI ckeditor integration on top of the [Sparky AI](https://github.com/electriccitizen/sparky_ai) base module.

## What it does

* Installs the ai_ckeditor module
* Installs a new AI Tone vocabulary
* Adds AI Assistant to the end of the toolbar for "basic_html"
* If the `basic_html` text format does not exist, this recipe will fail
* Sorry, Charlie. You'll need to install manually.

## Configuration requirements

There are not yet any working Config Actions to configure the AI Assistant plugin. So for now, you'll have to do it manually for each text format. 

For each text format where you want the AI Assistant enabled, add the recommended AI Tools under CKEditor 5 plugins.

### Recommended configuration: ###

**Tone** (Enable) 
* Choose the new AI Tone vocabulary for tone options.
* All other options can be left on default

**Summarize** (Enable)
* Default options

**Reformat** (Enable)
* Default options
* Note: We can reconsider this is a default option but I think it is kind of good?
  * It uses this prompt: 
  * Please fix this text to be marked up with semantic HTML using only lists, headers, or paragraph tags:

**Generate with AI** (Enable)
* Default options

**Fix spelling** (Enable)
* Default options

### Other options

**Translate**
* Only applicable to multingual sites

**Help and support**
* Dumb












* Permissions: manually update permissions for the roles who are allowed to have AI generated alt text (typically all content editors and managers.)




