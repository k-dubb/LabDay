##Ember.js

**What problem does it solve? How does it do it (conceptually)?**
1. Convention over configuration: Small choices are made for you (like in Rails). Stuff you didn't know you need is already there. 
2. Data Binding: Ember's Handlebars templates update automatically when data changes. Updated data only causes a single DOM update even if the same piece of data was updated several times.
3. Caching + Computed Properties: Let you declare functions as properties. Handy for taking one or more normal properties & transforming or manipulating their data to create a new value. Makes your code cleaner. Ember caches the value of the computed properties until one of the dependent properties change. It then recalculates the value of the computed property & caches it again. This is great for when you want to re-factor your code. 
    
**Why would I use it? What are the alternatives?**
1. Manages complexity of a large application. 
2. You write less code!
3. Alternatives: Angular, Backbone, Polymer, KnockoutJS, etc.

**What is the history of this technology? Who built it and why? Who is maintaining it?**
1. Ember was developed open source in 2011 under the MIT license. It's a full front-end framework utilizing common idioms and best practices.
2. It's been been used by sites like Groupon, Vine, Live Nation, and Chipotle. And in 2015 had over 200,000 downloads on github.
3. Maintained by the Ember Core Team: http://emberjs.com/team/

**What is your opinion on the technology after having built something with it?**

##How to install Ember.js

#####Using Node.js:

npm install -g ember-cli@2.3

#####Create a new application:
ember new ember-quickstart

#####Start the server:
ember serve