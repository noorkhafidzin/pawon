Plugin:
- Intro-Skipper:
  ```
  https://intro-skipper.org/manifest.json
  ```
- file-transform (media-bar):
  ```
  https://www.iamparadox.dev/jellyfin/plugins/manifest.json
  ```
- mal-metadata:
  ```
  https://raw.githubusercontent.com/ryandash/jellyfin-plugin-myanimelist/main/manifest.json
  ```
- mal-sync:
  ```
  https://raw.githubusercontent.com/iankiller77/MyAnimeSync/main/manifest.json
  ```
- jellyfin-enhanced:
  ```
  https://raw.githubusercontent.com/n00bcodr/jellyfin-plugins/main/10.11/manifest.json
  ```

Custom css:
- Login disclaimer:
  ```html
  Buat akun ke <a href="https://wizarr.home.noorkhafidzin.com/j/DAPTARCUY">sini</a>.
  ```
- Custom css:
  ```css
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/presets/kaleidochromic_preset.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/fixes.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/jf_font.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/base.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/accentlist.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/rounding_circlehover.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/smallercast.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/episodelist/episodes_compactlist.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/header/header_transparent.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/login/login_minimalistic.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/fields/fields_border.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/cornerindicator/indicator_floating.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/type/colorful.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/titlepage/title_simple-logo.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/progress/floating.css');
  
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/effects/hoverglow.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/effects/glassy.css');
  @import url('https://cdn.jsdelivr.net/gh/CTalvio/Ultrachromic/effects/pan-animation.css');
  
  #loginPage {
    background: transparent !important;
  }
  
  /*Style backdrop*/
  .backdropImage {filter: blur(18px) saturate(120%) contrast(120%) brightness(40%);}
  
  .homeSectionsContainer {
    position: relative;
    width: 100%;
    backdrop-filter: blur(15px);
    background: linear-gradient(
      to bottom,
      rgba(0, 0, 0, 0) 0%,       
      rgba(0, 0, 0, 0) 57vh,    
      rgba(0, 0, 0, 0.3) calc(57vh + 10vh),
      rgba(0, 0, 0, 0.6) 100%    
    );
  }
  
  
  /*SSO Login*/
  a.raised.emby-button {
    padding: 0.4em 1em;
    color: inherit !important;
  }
  
  .disclaimerContainer {
    display: block;
  }
  
  /*Media Bar Trailer fix for Zen browser*/
  .backdrop.with-video { mask-composite: intersect; }
  ```