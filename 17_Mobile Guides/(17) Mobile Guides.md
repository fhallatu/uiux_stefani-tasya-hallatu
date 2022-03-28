# Visual Design
------------------------------------------------------


## Adaptivity and Layout
======================================================

    1. 12.9" iPad Pro       1024x1366 pt ( 2048x2732 px @2x )
    2. 11" iPad Pro         834x1194 pt ( 1668x2388 px @2x )
    3. 10.5 iPad Pro        834x1194 pt ( 1668x2388 px @2x )
    4. 9.7" iPad Pro        768x1024 pt ( 1536x2048 px @2x )
    5. 7.9" iPad Mini       768x1024 pt ( 1536x2048 px @2x )
    6. 10.5" iPad Air       834x1112 pt  ( 1668x2224 px @2x )

### 1. Auto Layout

Using auto layout, you can define rules ( known as constraints ) that govern the content in your app

    - Using auto layout, you can define rules ( known as constraints ) that govern the content in your app
    - A safe area defines the area within a view that isn't covered by a navigation bar, tab bar, toolbar, or other views a view controller moght provide.
    - Adhere to the system-define safe areas and layout margins

### 2. Auto Layout Size Classes

A view may prossess any combination of size classes :
   
    - Regular width, regular height
    - Compact width, compact height
    - Regilar width, compact height
    - Compact widht, regular height

### 3. General Layout Considerations

    1. Ensure that primary content is clear at its default size
    2. Maintain an overall consistent appearance throughout your app.
    3. Use visual weight and balance to convey importance
    4. Use alignment to ease scanning and to communicate organization and hierarchy
    5. if possible, support both portrait and landscape orientations
    6. Be prepared for text-size changes
    7. Provide ample touch targets for interactive elements
    8. Preview your app on multiple devices
    9. Apply readability margins ehwn displaying text on larger devices

### 4. Animation

    - Use animation and motion effects judicilously
    - Strive for realism and credibility
    - Use consistent animation
    - Make animations optional

### 5. Branding
 
    - Incorporate refined, unobtrusive branding
    - Don't let branding get in the way of great app design
    - Defer to content over branding
    - Resist the temptation to display your logo throughout your app
    - Adhere to apple's trademark guidelines

### 6. Color

    - Don't rely solely on color to differentiate between objects or communicate important information
    - Use color judiciously for communication
    - Consider choosing a limited color palette that coordinates with your app logo
    -  Consider choosing a color to indicate interactivity throughout your app
    - Provide two versions of your accent color to make sure it looks good in both light and dark modes
    - Avoid using the same color for interactive and noninteractive elements
    - Consider how artwork and translucency affect nearby colors
    - Test your app's color scheme under a variety of lighting conditions
    - Consider how true tone display affect color
    - Consider how you use of color might be perceived in other countries and cultures
    - avoid using colors that can make it hard for people to perceive content in your app

### 7. Dark Mode

    - Comply with the appearance mode people choose settings
    - Tets your designs in both light and dark appearances
    - Ensure that your content ramains comfortably legible in dark mode when the contrast and transparency accessibility settings

### 8. Launch Screen

    - Design a launch screen thet's nearly identical to the first screen of your app
    - Avoid including text on your launch screen
    - Downplay launch
    - Don't advertise

### 9. Terminology

    - Use familiar, understandable words and phrases
    - Keep interface text xlear and concise
    - Identify interactive elements appropriately
    - Avoid language that might sound patronizing
    - Strive for informal, friendly tone
    - Be careful when useng humor
    - Use relevant anmd consistent language and imagery
    - Refer to dates accurately

### 10. Typography for IOS

San fransisco ( SF ). San fransisco is a sans serif type family thaht inludes SF Pro, SF Pro Rounded, SF Mono, SF Compact, and SF Compact Rounded. SF Pro is the system font in IOS, macOS, and tvOS; SF Compact is the system font in watchOS. Designed to match the visual clarity to the platform Uls, the system fonts are legible and neutral.

# Mobile Guide 
------------------------------------------------------

## Theme
======================================================

You'll need to meet high expetation for quality and functionality

Three Primary themes

    - Clarity
    - Deference
    - Depth

## Interface Essentials
======================================================

    - Bars
    - Views
    - Controls

## APP Architecture
======================================================

### 1. Launching

    - Provide a launch screen
    - Launch in the appropriate orientation
    - Avoid asking for setup information up front
    - Avoid showing in-app licensing agreements and disclaimers
    - Restore the previous state when your app restarts
    - Don't encourage rebooting
    - Avoid asking people to rate your app too quickly or too often

### 2. Onboarding

    - Provide onboarding that helps people rnjoy your app, not just set it up
    - Get to the action quickly
    - Anticipate the ne need for helps
    - Stick to the essentials in tutorials
    - Make learning fun and discoverable

### 3. Loading

    - Make it clear when loading is occurring
    - Show content as doon as possible
    - Educate or entertain people to mask loading time

### 4. Modality

    - Use modality when it makes sense
    - Reserve alerts for delivering essential, ideally actionable and information
    - keep modal tasks simple, short, and narrowly focused
    - Consider using a fullscreen modal style for immersive content or a complex task
    - Always include a button that dismisses the moadla view
    - When necessary, help people avoid data loss by getting confirmation before closing a modal view
    - Make it easy to identify a modal view's task
    - Coordinate the modal view's appearance with your app
    - Choose a modal transition style that makes sense in your app

### 5. Navigation Type

    1. Hierarchical Navigation
    2. Flat Navigation
    3. Content-Driven

### 6.  Navigation Tips

    - Always provide a clear path
    - Design an information structure that make it fast and easy to get to content
    - Use touch gestures to create fluidity
    - Use standart navigation components
    - Use a navigation bar to traverse a hierarchy of data
    - Use a tab bar to present peer categories of content or functionality
    - On iPad, use a split view instead of a tab bar
    - Use a page control when you have multiple pages of the same type of content

### 7. Accesing User Data and Resources

    - Request permission only when your app clearly needs access to the data or resource
    - Request permission at launch only when the data or resource is necessary for your app to function
    - Write copy that clearly describes how your app uses the data or resource you're requesting

### 8. Settings

    - Infer what you can from the system
    - Thoughtfully prioritize configuration option within your app
    - Expose infrequently change configuration options in settings
    - Provide shortcuts to Settings when appropriate

## Icons and Image
======================================================

Supply high-resolution images for all artwork in your app, for all devices app supports

    - Embrace simplicity
    - Provide a single focus point
    - Design a recognizeable icon
    - Kepp the background simple and avoid transparency
    - Use words only when they're essential or part of a logo
    - Don't oncludes photos, screenshots, or interface elements
    - Don't use replicas of Apple hardware products
    - Don't place your app icon throughout the interface
    - Test your icon against different wallpapers
    - Keep icon corners square ( for IOS )

### Image Size and Resolution

Good idea to use these built-in icons as much as possible because they're familiar to people

    - Use system icons as intended
    - Provide alternative text labels for icons
    - Design a custom icon if you can't find a system-provided one thet meets your needs

## Bars
======================================================

### 1. Navigation Bars

    - Consider temporarily hiding the navigation bar to provide a more immersive exoeru=ience
    - Consider showing the title of the current biew in the navigation bar
    - Use a large title when you want yo provide extra emphasis on context
    - Consider hiding the border of a large-title navigation bar
    - Consider using a segmented control in a navigation bar to flatten your app's information hierarchy

### 2. Search Bars

    - Use a search bar intead of a text field to implement search
    - Enable the clear button
    - Enable the cancel button when appropriate
    - If necessary, provide hints and context in a search bar
    - A scope bar can be added to a search bar to let people refine the scope of a search

### 3. Sidebars

    - Apply the correct appearance to a sidebar
    - Use a sidebar to organize information at the app level
    - WHen possible, let people customize the contents of a sidebar
    - Don't prevernt people from hifing the sidebar
    - Kepp titles in the sidebar clear and concise
    - in general, refrain from exposing more than two levels of hirarchy within a sidebar

### 4. Status Bars

    - Use the system-provided status bar
    - Coordinate the status bar style with your app design
    - Obscure content under the status bar
    - Consider temporarily hiding the status bar when displaying full-screen media
    - Avoid permanently hiding the status bar

### 5. Tab Bars

    - Use a tab bar only to enable navigation, not to help people perform actions
    - Use the minimum niber of tabs required to clarify your information hierarchy and helo people navigate your app
    - in a iPadOS app, consider using a sidebar instead of a tab bar
    - Avoid hiding the tab bar when people navigate to different areas in your app
    - Avoid removing or disabling a tab when its content is unavailable
    - Ensure that tabs affect the view that's attached to the tab bar, not views elsewhere onscreen
    - Use a badge to communicate unibtrusively
    - Consider using SF symbols to provide scalable, visually consistent tab bar items

# Fundamental Tips
------------------------------------------------------

## Size
======================================================

    - Structure your contrnt in just one column, Users scroll down to see all the content
    - Pay attention : you have to decide which information is important enough to make it to a smartphone design. If something dosesn't need to be there, skip it, or place it under a menu or on anothe page

## Screen Orientation
======================================================

    - On mobile devices, users have the option to change the screen orientation if they want. 94% of users use their smarthphone vertically while 6% do so horizontally
    - 49% of users prefer to use their mobil phones woth just one thumb

## Screen Orientation
======================================================

    - On a mobile device, users don't have a mouse or a physical keyboard to rely on. To type or select elements, mobile device users have to use their touchscreens
    - Offer them a keyboard
    - Make sure that the buttons are big enough to be tapped with a finger

## Seamless Design
======================================================

    This means that your design shoul be recognizable independently of whether ypur users go for the mobile or the desktop app