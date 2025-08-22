[![Typing SVG](https://readme-typing-svg.demolab.com?font=Handjet&size=50&pause=1000&color=7D10D2&background=FFFFFF00&center=true&vCenter=true&repeat=false&random=true&width=435&lines=%C2%BFQu%C3%A9+estoy+escuchando%3F)](https://git.io/typing-svg)
![My scrobbles](https://lastfm-recently-played.vercel.app/api?user=ChrisRomm&width=500&header_style=compact_stats_only&show_user=footer&footer_style=normal&border_radius=15&bg_color=121418)

# Diagrama rizomático y caótico

Un intento de representar la **digitalidad, el espacio y la réplica** en un flujo rizomático:

```mermaid
flowchart TD
  A[digitalidad]:::n <--> B[espacio-latente]:::n
  B <--> C[réplica]:::n
  C <--> D[eco]:::n
  D <--> E[ruido]:::n
  E <--> F[caos]:::n
  F <--> G[fractales]:::n
  G <--> H[ensamblaje]:::n
  H <--> A
  C <--> F
  B <--> G

  %% Estilos caóticos
  classDef n fill:#8ee5ff,stroke:#111,stroke-width:2px,color:#000,font-weight:bold;

  %% Animaciones y caos simulados
  linkStyle 0,1,2,3,4,5,6 stroke:#ff007f,stroke-width:2px,stroke-dasharray:5 5;
  linkStyle 7,8 stroke:#ffae00,stroke-width:3px;
  linkStyle 9 stroke:#00ffcc,stroke-width:2.5px,stroke-dasharray:3 2;
