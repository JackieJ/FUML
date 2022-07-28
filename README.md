# FUML(WIP)
Flowing UML - Making System Design Fun Again

## What's This
A UML/PlantUML based dynamic system design simulator. It features:
* basic UML/PlantUML language support
* common system components with their behaviors simulated and configurable (db schema, partitions, IO patterns, network, API, etc)
* configurable live data flow simulation among system components
* mocking system components IO and isolation testing
* configurable system verifier 
* configurable load tester
* toy system factory: docker-compose generator based on UML diagrams

## Motivation 
### Preface - My Casual Love for UML
I love seeing jibberish I write gets rendered into something beautiful, hence my love for [Latex](https://www.latex-project.org/) and [UML](https://www.uml.org/), as well as their visual companions [TexMaker](https://www.xm1math.net/texmaker/) and [PlantUML](https://plantuml.com/). I religiously write .tex files for my college papers, personal statements, and even music sheets using the [Latex and Lilypond combo](https://lilypond.org/doc/v2.21/Documentation/usage/latex). 

As for UML, I started using its visual companion PlantUML back in college to help translate my computer architecture class notes to diagrams because of its amazing ability to render from a very intuitive set of declarative syntax. Now as an engineer with a few years of experience under belt, I still regularly use PlantUML to help me visualize design and produce system diagrams for documentation, presentation. I know PlantUML is extremely customizable and offers a lot more than just connecting components and drawing silly mindmaps, for example, its preprocessing capability (similar to [C macros](https://gcc.gnu.org/onlinedocs/cpp/Macros.html) prefixed with `#`) and [stdlib](https://github.com/plantuml/plantuml-stdlib) that contains tons of icons and static assets that can be used to enhance diagram visual. But I never grew beyond PlantUML's basic features because of how useful the basics already are. However, one thing I wish I could easily get out of PlantUML is live simulation of systems. I can already imagine how much more painless designing complicated distributed systems would be if we are able to properly simulate them every step of the way to incrementally verify business logic, consistency, availability and expected performance. Hence the birth of FUML. For this project, I may commit more than just casual and delve deeper into PlantUML's advance features and potentially rabbit-hole myself into its codebase.

## Research
### What PlantUML Already Offers
### Helpful Python Libs and Binding
### 
## Project Structure
## Installation
## Usage
