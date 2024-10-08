# Workshop Day 01

## Intro - Whoami

- I am a Coach @MLH
- I also teach CS and robotics at grades 6-12
- I like Star Wars, lettuce, and indie games

## What type of workshop series will this be

- I like to keep it interactive like an IRL classroom so I will ask for your 
  input but no pressure to respond!
- I will try to justify all the major design decisions I make and highlight the
  thinking process behind all of them.
- series 
  - will focus more on UX + DX than specifics of each element / selector / etc.
  - will drop resources for further learning
- first day will be less coding more designing + intro to web-dev
  - introduce lots of learning resources
  - introduce sources for making more informed decisions
- Why JAMstack for open source?
  - documentation builder
  - static websites are easier than dynamic websites
  - 60% of the web is wordpress -> static websites
    - https://w3techs.com/technologies/details/cm-wordpress
    - other 40% is probably shops + webapps + social media 

## Agenda

- What is a JAMStack website
  - Building your first JAMStack website with no code! (11ty)
  - Picking a website tech stack to start with!
  - Comparing JAMstack websites to other website builders (why 11ty)
  - Vanilla vs JAMStack
- Mapping out the learning path for mastering the JAMStack pattern
  - tour roadmaps.sh
  - tour the odin project
- Designing our own JAMStack website
  - Figma crash course
  - Content planning
  - Setting up GitHub issues + projects
  - Developer tooling setup in GitHub Codespaces

## What is a JAMStack website

Resource
- https://jamstack.org/
- https://youtu.be/EPir6uxr1o8?si=9AcwdevWRVtNmnMl

- Architectural style that separates content from experience
  - writing HTML by hand = carpal tunnel
  - writing md by hand = lightweight
  - DRY principles
- Building from a template + code tour
  - content vs templates vs static site
- Explaning our tech stack for the rest of the series
  - architecture: JAMstack (vs MPA - simplest, SPA - less reloads, hybrid)
  - front-end: vanilla
  - back-end: none
  - db: none
  - component framework: none
  - meta-frameworks: 11ty
- SPA vs MPA vs Hybrid
  - MPA - simple DX but full page reloads 
  - SPA - browser makes html but slow load times
  - Hybrid - best of both?
  - JS = slow, less JS => faster
- why use a meta-framework
  - hybrid static + SSR
  - hydration optimization
  - emphasis on templating
  - file-based routing

## Learning path for mastering JAMStack pattern

Resource
- https://roadmap.sh/
- https://www.theodinproject.com/

- start with 11ty tutorial
  - build out the tutorial, look up HTML elements you don't recognize
  - identify what type of tooling you're looking at
    - learn about NPM, bundlers, component frameworks, css frameworks, db, etc.
  - recognize that software engineers are lazy at heart, DRY principles ->
    we rely on libraries a lot
    - dangers of dependencies
    - learning shortcuts good vs bad
    - use vanilla -> minimal frameworks -> anything you'd like
    - you only have to learn these things once in your entire career
    - ex: https://x.com/t3dotgg/status/1830452181834850596
    - ex: https://picocss.com/
- picking what to learn next
  - what are your goals
  - current state of development
    - https://survey.stackoverflow.co/2024/technology/
  - getting a job
    - https://stackshare.io/stacks
    - job application
    - company technical blogs
    - company github

## Designing our own JAMStack website

- Figma and btw Penpot (FOSS) exists
- Quick crash course on figjam / tldraw for lo-fi
- Quick crash course on figma / penpot for hi-fi
  - handy shortcuts + modifiers
  - get used to using frames
  - auto-layout
  - variables + defaults
  - components
  - importing libraries

## Building our own JAMstack website
