<nav class="navigation">
  <ul class="navigation-list">
    <li><a href="#home">Home</a></li>
    <li><a href="#home">About</a></li>
    <li><a href="#home">Contacts</a></li>
  </ul>
</nav>
<style>
  nav.navigation {
		border:1px solid black;
    position:fixed;
    background:white;
    top:0;
    width:100%;
    padding:0.5rem;
  }
  ul.navigation-list {
    display:flex;
    list-style-type: none;
    padding:0;
    margin:0;
    height:max-content;
  } 
  ul.navigation-list > li {
    margin:0 0.5rem;
  }
  ul.navigation-list a {
    display:block;
    text-decoration:none;
    color:black;
    padding:1rem;
  } 
  ul.navigation-list a:hover {
    background:green;
  }
  
</style>