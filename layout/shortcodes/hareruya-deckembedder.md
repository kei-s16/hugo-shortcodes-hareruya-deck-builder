<div>
  <script type="module" async crossorigin src="https://embed.deck.hareruyamtg.com/deckembedder.js"></script>
  <deck-embedder
    deckid="{{ .Get "deckid" }}"
    {{ if .Get "token"}}
      token="{{ .Get "token" }}"
    {{ end }}
    {{ if .Get "height"}}
      height="{{ .Get "height" }}"
    {{ else }}
      height="640"
    {{ end }}
  />
</div>
