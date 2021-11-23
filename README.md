# Visual Studio Code setup for Ruby development

## **Code completion**
### Ruby Solargraph
1. Install the [Ruby Solargraph extension](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph) 
2. Install the solargraph gem

    ```ruby
    gem install solargraph
    ```
### Endwise
1. Install the [endwise extension](https://marketplace.visualstudio.com/items?itemName=kaiwood.endwise)

## **Go to definition**
For this to work properly, you first need the above mentioned Ruby Solargraph extension and gem.
### Ruby
1. Install the [Ruby extension](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby). 
2. Configure the following setting on VSCode

    ```json
    "ruby.intellisense": "rubyLocate"
    ```
## Debug
### VSCode rdbg Ruby Debugger 
1. Install the [VSCode rdbg Ruby Debugger extension](https://marketplace.visualstudio.com/items?itemName=KoichiSasada.vscode-rdbg) 
2. Install the debug gem

    ```ruby
    gem install debug
    ```

## **Lint**
### Standardrb
For this to work properly, you need the above mentioned [Ruby extension](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby).



1.  Enable the Ruby language server in your settings

2.  The Ruby:Lint option will direct you to the settings.json file, enable standard linting by adding the following:
    ```json
    "ruby.lint": {
    "standard": true
    }
    ```
3. Reload your window to enable the language server and linting. You can confirm that linting is happening by selecting the "Ruby Language Server" in the Output tab.

