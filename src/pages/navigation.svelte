<script>
  export let theme = "light";
  
</script>
<nav class="navigation {theme}">
  <ul class="navigation-list">
    <li class="theme-button">
      <slot name="theme">

      </slot>
    </li>
    <li><a href="#home">Home</a></li>
    <li><a href="#home">About</a></li>
    <li><a href="#home">Contacts</a></li>
    
  </ul>
</nav>
<style>
  nav.navigation {--bg:white;--color:black;
    background:var(--bg);
    width:100%;
    padding:0.5rem;
    box-shadow:0 2px 0.25rem 0 #111; 
  }
  nav.navigation.dark {--bg:hsl(219,13%,18%);--color:white;}
  ul.navigation-list {
    display:flex;
    align-items: center;
    list-style-type: none;
    padding:0;
    margin:0;
    height:max-content;
  } 
  ul.navigation-list > li {margin:0 0.5rem;transition:background 0.3s ease;}
  ul.navigation-list :is(a, button) {
    display:block;
    text-decoration:none;
    color: var(--color);
    padding:0.5rem;
  } 
  ul.navigation-list >li:hover {background:green;}
  li.theme-button {border-radius:50%;}
</style>