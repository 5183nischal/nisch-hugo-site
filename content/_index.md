+++
title = 'Home'
[menu]
  [menu.main]
    name = 'Home'
    weight = 1
+++

<style type="text/css">
.home h1 {
  font-size: 2em;
  font-style: normal;
}

.home h2 {
  font-style: italic;
  font-weight: normal;
}

.home h3 {
  font-weight: normal;
  padding-right: 18em;
}

.profile-image {
  position: absolute;
  top: 10.5em;
  right: 0;
  width: 18em;
  height: auto;
  object-fit: cover;
  margin-right: 3.7em;
  border-radius: 10px;
}

.publications {
  margin-top: 1.5em;
}

.publications h2 {
  margin-bottom: 0.5em;
}

.publications ul {
  list-style-type: none;
  padding: 0;
}

.publications a {
  color: #000000;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  padding: 2px 4px;
  transition: color 0s, background-color 0s, border-bottom 0s;
}

.publications a:hover {
  color: white;
  background-color: #005077;
}

.publications a:hover {
  position: static;
  inset: auto;
}

/* Media Queries for Responsive Design */
@media screen and (max-width: 768px) {
  .home h3 {
    padding-right: 0;
    margin-bottom: 20em; /* Space for the image below */
  }

  .profile-image {
    position: relative;
    top: auto;
    right: auto;
    width: 100%;
    max-width: 18em;
    margin: 1em auto;
    display: block;
  }

  .publications {
    margin-top: 1em;
  }

  .publications a {
    display: block;
    padding: 0.5em 0;
  }
}

/* For very small screens */
@media screen and (max-width: 480px) {
  .home h1 {
    font-size: 1.5em;
  }

  .home h2 {
    font-size: 1.2em;
  }

  .home h3 {
    font-size: 1em;
    margin-bottom: 15em;
  }

  .profile-image {
    max-width: 15em;
  }
}
</style>

<h1 class="title">Nischal Mainali</h1>

<h3>
Hi, I'm Nischal and I am a PhD candidate in neuroscience at the Burak lab in the Hebrew university of Jerusalem.
I am interested in mathematical theories of cognition and understanding representational properties of biological and artificial minds.
</h3>

<img src="nisch.jpg" alt="Nischal Mainali" class="profile-image">
<div class="publications">
  <h2> Recent works</h2>
  <ul>
    <li><a href="#">❡ Mainali, N (<i>WIP</i>). "Solvable model of in-context learning in linear transformers."</a></li>
    <li><a href="https://www.biorxiv.org/content/10.1101/2024.06.11.597569v1">❡ Mainali, N., da Silveira, R., Burak, Y. (2024). "Universal statistics of hippocampal place fields across species and dimensionalities."</a></li>
    <li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3205286">❡ Mainali, et al. (2018). "Automated Classification of Modes of Moral Reasoning in Judicial Decisions."</a></li>
  </ul>
</div>
