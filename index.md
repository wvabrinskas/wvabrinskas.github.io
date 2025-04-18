<link
  rel="stylesheet"
  href="stylesheets/graph.css"
/>

<!-- Prepare a container for your calendar. -->
<script
  src="js/calendar.min.js"
>
</script>

<link type="text/css" rel="stylesheet" href="/stylesheets/main.css" />

<img src="media/profile-sqr.jpg" class="profile" width="200"/>

<div id="logo_stack">
<a href="https://twitter.com/wvabrinskas"><img src="media/x.png" class="logo" width="50"/></a>
<a href="https://github.com/wvabrinskas"><img src="media/github.png" class="logo" width="50"/></a>
<a href="https://www.linkedin.com/in/william-vabrinskas-31b307a8"><img src="media/linkedin.png" class="logo" width="50"/></a>
<a href="https://discord.gg/p84DYph4PW"><img src="media/discord.png" class="logo" width="50"></a>
<a href="https://mstdn.social/@wvabrinskas"><img src="media/mastodon.png" class="logo" width="50"></a>
<a href="https://bsky.app/profile/wvabrinskas.bsky.social"><img src="media/bluesky.png" class="logo" width="50"></a>
</div>


<div id="sponsor">
<iframe src="https://github.com/sponsors/wvabrinskas/button" title="Sponsor wvabrinskas" height="35" width="116" style="border: 0;"></iframe>
</div>

# Hello! 👋

### About me
- I am an avid iOS engineer with 10+ years of experience who's main focus is building modular and easy to use frameworks in Swift. I have many open source projects you can checkout on my github. 
- My passion is machine learning. I focus on that mainly in my spare time and work on learning as much as I can about the topic. 
- I enjoy hiking and nature photography. 
- I'm a maker.
- B.S. Degree in Toxicology

<p></p>
### Career

#### Current
- Uber - Senior iOS Engineer

#### Past
- Fox News - Lead Ad Tech iOS Engineer  
- Daily Mail - iOS Engineer 
- Elite Daily - iOS Engineer / Android Engineer 

# Posts 
### <a class="custom_link" href="pages/post/memory-capsules" > Huddle's newest feature: Memory Capsules</a>
Published: 04-05-2025
### <a class="custom_link" href="pages/post/huddle" > New app release: Huddle</a>
Published: 05-20-2024
### <a class="custom_link" href="pages/post/swift-arch" > A New Swift Architecture</a>
Published: 04-28-2023
# Apps 📱
### <a class="custom_link" href="https://apps.apple.com/us/app/huddle-get-together/id1668460364" > Huddle - Get together </a>
- Huddle is a unique social networking app that focuses on helping you connect with your loved ones in person and share personal posts with them. With Huddle, you can create a private network of friends and family that is completely offline and fully on device.

### <a class="custom_link" href="https://apps.apple.com/us/app/nowcast-commuter-weather/id1501885597" > Nowcast - commuter weather</a>
- Nowcast provides you with instant access to your commuter weather. It is a simple yet very effective app. You can set two time slots in which you would like weather to display. It will show you brief yet informative weather information for each of those times.

- It is perfect for the busy commuter looking to quickly decide on an outfit before leaving for work.

# Projects 📝
- [AI / Machine Learning](#ai--machine-learning)
- [Architectures](#architectures)
- [Algorithms](#algorithms)
- [UI](#ui)
- [General](#general)

---------------
### AI / Machine Learning
---------------
### <a href="https://github.com/wvabrinskas/Neuron">Neuron</a>
[![Tests](https://github.com/wvabrinskas/Neuron/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/wvabrinskas/Neuron/actions/workflows/tests.yml)

  - Neuron is a swift package I developed to help learn how to make neural networks. It is far from perfect and I am still learning. There is A LOT to learn here and I've just scratched the surface. As of right now this package provides a way to get started in machine learning completely in Swift.
  - Swift package support

### <a href="https://github.com/wvabrinskas/NeuronDatasets">NeuronDatasets</a>

  - Package contains machine learning datasets that are supported by the Neuron package.
  - Swift package support

### <a href="https://github.com/wvabrinskas/NeuronRemoteLogger">NeuronRemoteLogger</a>

  - Package that connects the Neuron package to various remote loggers like Weights and Biases
  - Swift package support

### <a href="https://github.com/wvabrinskas/Genetic">Genetic</a>
[![Tests](https://github.com/wvabrinskas/Genetic/actions/workflows/tests.yml/badge.svg)](https://github.com/wvabrinskas/Genetic/actions/workflows/tests.yml)
  - Genetic is a swift package that makes it incredibly simple to include the Genetic Algorithm within a project.
  - Swift package support

### <a href="https://github.com/wvabrinskas/NumSwift">NumSwift</a>
[![Tests](https://github.com/wvabrinskas/NumSwift/actions/workflows/tests.yml/badge.svg)](https://github.com/wvabrinskas/NumSwift/actions/workflows/tests.yml)
  - Adds array arithmetic to Swift
  - Swift package support

### <a href="https://github.com/wvabrinskas/Jumpiter">Jumpiter</a>
  - A macOS app that utilizes my Neuron and Genetic swift packages to play a simple game all on its own.

---------------
### Algorithms
---------------
### <a href="https://github.com/wvabrinskas/SwiftSearchTrie">SwiftSearchTrie</a>
[![Tests](https://github.com/wvabrinskas/SwiftSearchTrie/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/wvabrinskas/SwiftSearchTrie/actions/workflows/tests.yml)
  - A swift package that utilizes a trie data structure to build and provide quick and efficient search algorithm. 
  - Swift package support

### <a href="https://github.com/wvabrinskas/FareyAlgorithm">FareyAlgorithm</a>
  - "In mathematics, the Farey sequence of order n is the sequence of completely reduced fractions, either between 0 and 1, or without this restriction,[a] which when in lowest terms have denominators less than or equal to n, arranged in order of increasing size. With the restricted definition, each Farey sequence starts with the value 0, denoted by the fraction 0/1, and ends with the value 1, denoted by the fraction 1/1 (although some authors omit these terms)."

---------------
### Architectures
### <a href="https://github.com/wvabrinskas/HuddleArch">HuddleArch</a>
  - The architecture takes a lot from the RIBs architecture, with the idea of a builder and a router. Where the builder is responsible for creating the module and router with their respective dependencies. However instead of an interactor I am proposing the idea of a Module instead.
  - The architecture relies heavily on protocol definitions and generics. This allows for the architecture to be as extensible as possible. Instead of directly referencing a specific type, a protocol definition is used instead.
  - Swift package support

### <a href="https://github.com/wvabrinskas/SwiftlyRedux">SwiftlyRedux</a>
[![Tests](https://github.com/wvabrinskas/SwiftlyRedux/actions/workflows/Tests.yml/badge.svg?branch=master)](https://github.com/wvabrinskas/SwiftlyRedux/actions/workflows/Tests.yml)
  - A swift package that creates a new architecture for iOS development. It is very similiar to redux where there is one source of truth with a state manager object. 
  - This framework makes a major improvement to the redux architecture in that you can directly access members of the state and call updates to subjects all with type safety without ambiguity as to what you're updating. 
  - It is an incredibly modular architecure where the state calls out to its submodules without actually knowing what those modules do. Each module can be updated indvidually and pass its updates to the state object.
  - This allows for your app to be easily testable.
  - Combine support. 
  - Swift package support

---------------
### UI
---------------
### <a href="https://github.com/wvabrinskas/Paver">Paver</a>
  - lightweight UIView layout utility. It's effectively an extension on UIView allowing for quick constraint assignment to any view. It reduces the complexity of using the built-in AutoLayout by wrapping a lot of the verbose assignments to easy to read functions and variables.
  - Swift package support
 
### <a href="https://github.com/wvabrinskas/CalendarUI">CalendarUI</a>
  - A swift package for SwiftUI that allows you to quickly and simply add a full calendar to your SwiftUI projects.

---------------
### General
---------------

### <a href="https://github.com/wvabrinskas/SimpleApiClient">SimpleApiClient</a>
[![Tests](https://github.com/wvabrinskas/SimpleApiClient/actions/workflows/tests.yml/badge.svg)](https://github.com/wvabrinskas/SimpleApiClient/actions/workflows/tests.yml)
  - The most bare-bones api client you can imagine in Swift.
  - Swift package support
