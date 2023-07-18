# test graph


```mermaid
%%{init: {'theme':'forest'}}%%
  graph TD
    a --> b
```

```mermaid
%%{init: {'theme': 'base','themeVariables': {'darkMode': 'false', 'primaryColor': 'default','primaryTextColor': '#7C0000','primaryBorderColor': '#F8B229','lineColor': '#006100','secondaryColor': '#fff','tertiaryColor': '#7C0000', 'background' : '#f4f4f4'} }}%%
graph TD
    A[afff]-->B
    A[afff]-->C
    B-->D
    C-->D
```

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#AFEEEE',
      'primaryTextColor': '#000000',
      'primaryBorderColor': '#000000',
      'lineColor': '#000000',
      'secondaryColor': '#FFE5B4',
      'tertiaryColor': '#fff'
    }
  }
}%%
        graph TD
          subgraph section
          A[what is questions say?] -->|Get money| B(Go shopping)
          B --> C{Let me think}
          B --> G[/Another/]
          C ==>|One| D[Laptop]
          C -->|Two| E[iPhone]
          C -->|Three| F[fa:fa-car Car]
          style B fill:#bbf
          end
```

