# microfrontendReact
# 01 Basics of Microfrontends
  001 What is Microfrontend
  002 Overview
 003 Build Time Integration
004 A Build Time Integration
005 Project Setup
 006 Generating Products
 007 Background on Webpack
 008 More on Webpack
  009 Finishing Product List
 010 Scaffolding Container
# 02 Basics of Module Federation
 011 Implementing Module Federation
  012 Understanding Module Federation
  013 More on Module Federation
 014 Understanding Configuration Options
  015 Scaffolding Cart
 016 Cart Integration
017 Development Process
# 03 Sharing Dependencies Between Apps
 018 Using Shared Modules
 019 Async Script Loading
 020 Shared Module Versioning
021 Singleton Loading
  022 Sub App Execution Context
 023 Refactoring Products
  024 Consuming Remote Modules
  025 Refactoring Cart
 026 A Funny Gotcha
# 04 Linking Multiple Apps Together
  027 Overview
  028 Tech Stack
 029 Requirements That Drive Architecture Choices
  030 Dependency Installation
  031 Initial Webpack Config
 032 Creating and Merging Development Config
  033 Running Marketing in Isolation
  034 Wiring Up React
  035 Adding Pricing and Landing Pages
# 05 Generic Ties Between Projects
 036 Assembling App Component
 037 Assembling Container
038 Integration of Container and Marketing
 039 Why Import Mount Function
040 Generic Integration
 041 Reminder on Shared Modules
  042 Delegating Shared Module Selection
# 06 Implementing a CICD Pipeline
043 Requirements Around Deployment
 044 Path to Production
  045 Initial Git Setup
 046 Production Webpack Config for Container
 047 Production Webpack Config for Marketing
 048 Understanding CICD Pipelines
  049 Creating Container Action
- 050 Testing Pipeline
# 07 Deployment to Amazon Web Services
  051 S3 Bucket Setup
  052 Authoring a Bucket Policy
  053 Cloudfront Distribution Setup
054 Cloudfront Configuration
  055 Creating & Assigning Access Keys
 056 Rerunning Build
 057 A Small Error
 058 Webpacks PublicPath Setting
# 08 Microfrontend Specific AWS Config
- 059 Manual Cache Invalidations
 060 Automated Invalidation
 061 Successful Invalidation
 062 Setting Up Marketing Deployment
  063 Reminder on Production Domain
  064 Running Deployment
 065 Verifying Deployment
- 066 Production Style Workflow
# 09 Handling CSS in Microfrontends
 - 067 Adding a Header
 - 068 Issues with CSS in Microfrontends
- 069 CSS Scoping Techniques
  070 CSS in JS Libraries
  - 071 So Whats Bug
  072 Fixing Class Name Collisions
 073 Verifying Fix
# 10 Implementing Multi Tier Navigation
 074 Inflexible Requirements Around Navigation
 075 A Few Solutions
  076 Which History Implementation
 077 Surveying Our Current History Setup
 078 Using Memory History
 079 Why Strange Results
 080 Communication Between Apps
- 081 Communicating Through Callbacks
  082 Syncing History Objects
083 Running Memory History in Isolation
 084 Container to Child Communication
 085 Using Browser History in Isolation
# 11 Performance Considerations
  086 Starting Auth Project
 087 Adding Signin and Signup Forms
  088 A Deeper Dive on PublicPath
 089 Last Time for PublicPath
090 Integrating Auth into Container
 091 Adding Initial State to Memory History
092 Lazily Loading SubApps
093 Adding a Loading Bar
# 12 Authentication in Microfrontends
  094 Notes on Authentication
 095 Implementation Strategies
 096 Communicating Auth Changes
 097 Communicating Authentication State
 098 Allowing Signout
 099 Adding Auth Deploy Config
100 Verifying Deployment
# 13 Using Other Frontend Frameworks
 101 Initial Dashboard Setup
 102 More on Config
 103 Showing Dashboard
 104 Integration with Container
105 Protecting Access to Dashboard
106 Deploying Dashboard
 107 Verifying Deployment
