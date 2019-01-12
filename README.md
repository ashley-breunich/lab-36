![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 36: Context

### Author: Ashley Breunich

### Links and Resources
* [github url](https://github.com/ashley-breunich/lab-36)
* [code sandbox](https://codesandbox.io/s/13kvzxy9o4)
* [Front End](https://13kvzxy9o4.codesandbox.io/)

### Modules
#### `index.js`
##### Exported Values and Methods

###### `CLASS Main'
--> App Component


#### `app.js`
##### Exported Values and Methods

###### `CLASS App'
--> Decrementer Component

--> Counter Component

--> Incrementer Component


#### `settings/counter-context.js`
##### Exported Values and Methods

###### `CLASS SettingsProvider'
--> SettingsContext.Provider Component

###### `constructor()`
<-- props

Sets the state { count, increment, decrement }

###### `increment()`
<-- event

Sets: this.state.count 

###### `decrement()`
<-- event

Sets: this.state.count 


#### `components/counter/counter.js`
##### Exported Values and Methods

###### `CLASS Counter`
--> SettingsContext.Consumer which wraps the context.count span


#### `components/decrementer/decrementer.js`
##### Exported Values and Methods

###### `CLASS Decrementer`
--> SettingsContext.Consumer which wraps the decrementer button


#### `components/decrementer/incrementer.js`
##### Exported Values and Methods

###### `CLASS Incrementer`
--> SettingsContext.Consumer which wraps the incrementer button


#### Tests
* How do you run tests?
* What assertions were made?
* What assertions need to be / should be made?

#### UML
[Link to UML]('assets/lab35-uml.jpg')