<p align="center">
  <a href="http://www.audallabs.com">
    <img alt="Audal Labs Logo" src="https://static.audallabs.com/logodark.png" width="90" />
  </a>
</p>

<h1 align="center">gatsby-plugin-emotion-ssg</h1>

<h4 align="center">Replace Gatsby's default renderer with Emotion's, to ensure correct rendering of Emotion-styled components during SSG.</h4>

<pre align="center">npm i gatsby-plugin-emotion-ssg</pre>

#### Why should I use this?
`gatsby-plugin-emotion` might work for your use case. It might not. This plugin works where that one does not, by replacing the Gatsby SSG renderer, and inlining critical CSS styles. It's a more heavy-handed approach, but works in almost every use-case.
