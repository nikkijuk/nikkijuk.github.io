<p align="center">
  <a href="https://revealjs.com">
  <img src="https://hakim-static.s3.amazonaws.com/reveal-js/logo/v1/reveal-black-text.svg" alt="reveal.js" width="450">
  </a>
  <br><br>
  <a href="https://github.com/hakimel/reveal.js/actions"><img src="https://github.com/hakimel/reveal.js/workflows/tests/badge.svg"></a>
  <a href="https://slides.com/"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>
</p>

reveal.js is an open source HTML presentation framework. It enables anyone with a web browser to create fully featured and beautiful presentations for free. [Check out the live demo](https://revealjs.com/).

The framework comes with a broad range of features including [nested slides](https://revealjs.com/vertical-slides/), [Markdown support](https://revealjs.com/markdown/), [Auto-Animate](https://revealjs.com/auto-animate/), [PDF export](https://revealjs.com/pdf-export/), [speaker notes](https://revealjs.com/speaker-view/), [LaTeX support](https://revealjs.com/math/), [syntax highlighted code](https://revealjs.com/code/) and much more.

<h1>
  <a href="https://revealjs.com/installation" style="font-size: 3em;">Get Started</a>
</h1>

## Documentation
The full reveal.js documentation is available at [revealjs.com](https://revealjs.com).

## Online Editor
Want to create your presentation using a visual editor? Try the official reveal.js presentation platform for free at [Slides.com](https://slides.com). It's made by the same people behind reveal.js.

## License

MIT licensed

Copyright (C) 2011-2020 Hakim El Hattab, https://hakim.se

## x

mermaid diagram

```mermaid
flowchart TB
    subgraph app
        direction LR
        main --> navigation
        main --> configuration
    end

    subgraph feature
        direction LR
        feature_ui --> feature_bloc
    end

    subgraph repository
        direction LR
        repository_impl 
    end

    subgraph domain
        direction LR
        repository_api --> domain_model
    end

navigation --> feature_ui
configuration --> repository_api
configuration --> repository_impl
feature_bloc --> repository_api
repository_impl --> repository_api
repository_impl --> domain_model
```

# y 

mermaid diagram

```mermaid
flowchart TB
    subgraph app
        direction LR
        main --> navigation
        main --> configuration
    end

    subgraph features
        direction LR
        subgraph feature
        end
        subgraph feature2
        end
        subgraph feature3
        end
    end

    subgraph integrations
        providers
        services
        plugins
    end

    subgraph repositories
        subgraph repository
        end
        subgraph repository2
        end
    end

    subgraph domain
        repository_interface --> domain_model
    end

    configuration --> integrations
    configuration --> repositories
    configuration --> features
    configuration --> domain
    repositories --> domain
    features --> domain
    navigation --> features

    features --> repositories
    repositories --> integrations   
```


