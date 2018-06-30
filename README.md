![Logo](https://raw.githubusercontent.com/Raathigesh/SemanticEdit/master/assets/SemanticEditLogo.png)

# SemanticEdit - http://raathigesh.com/semantic/
Real-time Preview Enabled [Semantic UI](http://raathigesh.com/semantic/) Composer

## How?
Copy the following Semantic-UI markup to [Semantic Edit](http://raathigesh.com/semantic/) editor.

```html
<div class="ui card">
  <div class="image">
    <img src="http://semantic-ui.com/images/avatar2/large/kristy.png">
  </div>
  <div class="content">
    <a class="header">Kristy</a>
    <div class="meta">
      <span class="date">Joined in 2013</span>
    </div>
    <div class="description">
      Kristy is an art director living in New York.
    </div>
  </div>
  <div class="extra content">
    <a>
      <i class="user icon"></i>
      22 Friends
    </a>
  </div>
</div>
```
You could copy and paste any [Semantic UI components](http://semantic-ui.com/elements/button.html).

## But Why?
[Semantic UI](http://semantic-ui.com) is an awesome library with excellent components that you can use to quickly
build web interfaces. But I felt like it would be nicer if we can compose bunch of elements and see in realtime how they
fit together. That's why Semantic Edit.

## Features
- Beautifier

## Run & Build from sourcecode
Clone the sourcecode: 
```
git clone https://github.com/Raathigesh/semantic-edit.git
```
Install the dependencies:

```
npm install
```

Install webpack and the development server:

```
npm i webpack-dev-server webpack -g
```

You can simply run webpack build using this command: 

```
npm run build
```

If you want to run with webpack-dev-server simply run this command: 

```
npm run dev
```

Open the web browser to `http://localhost:8080/`


## What's Under the Hood?
JavaScript! 

SemanticEdit uses the following
- [Semantic UI](http://semantic-ui.com)
- [React JS](https://facebook.github.io/react/)
- [WebPack Build System](https://webpack.github.io/)
- [Ace Editor](https://ace.c9.io/#nav=about) & [react-ace](https://www.npmjs.com/package/react-ace)

## That's It?
I'm hoping to add features as I move along. Got a feature suggestion? Would love to hear about it. Please create a new issues. 

## Stay Updated
- Follow us [@SemanticEdit](https://twitter.com/SemanticEdit)
