# Tabnews Studies

## Foundation - Node.js
```node -v``` -> checks the current version of Node
```npm ls``` -> checks available versions
npm (node version manager)
lts (long term support)

```npm install lts/hydrogen``` -> installs this specific version of Node
```npm alias default lts/hydrogen``` -> sets it as the default version

creates a .nvmrc file
adds lts/hydrogen to the file

```npm install``` -> checks and installs the version

rc -> run command

## Walls - Next.js
Next.js is a web development framework that provides numerous conveniences, both during development and deployment. It's one option among many.

Next.js controls/orchestrates everything that happens, seamlessly in both the backend and frontend. The content, the substance, is the responsibility of other more specific modules. Next.js is one of the best framework/web host integrations.

#### Installing Next.js
Let's create a manifest file that will list the project's dependencies; this file is called package.json. This ensures that anyone running the project knows the correct version to use.

```npm init```
```npm install next@13.1.6```

#### Installing React

```npm install react@18.2.0```
```npm install react-dom@18.2.0```


### Protocols
HTTP - Hypertext Transfer Protocol
FTP - File Transfer Protocol
SMTP - Simple Mail Transfer Protocol
...

A protocol is an agreement, a combination, a standard set of rules.

Setting up a web server
Using the "next dev" dependency
Access package.json
Add the command "dev": "next dev" to the scripts section

```npm run dev``` (executes the created shortcut)

The web server has started, but it didn't find anything and terminated.

### File-Based Routing
Next.js operates with file-based routing.

Create a folder called "pages" at the root of the project, and then create a file named "index.js."

In Next.js, any folder containing a JS or TS file becomes a public route.

Navigating the line that separates Next.js from React.

Next.js bridges the connection between the external world (routes) and what will be delivered (complete objects), which are the React components.

Within the index.js file, we write the React component, which is nothing more than a normal JavaScript function, naming this function "Home."

```javascript
function Home(){
    return <h1>Test</h1>;
}

export default Home;
```

Run `npm run dev`

