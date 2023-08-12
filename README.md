<h1 align="center">

</h1>

<p align="center">
  .news 
  <br>
  <br>

  <img src="https://img.shields.io/badge/made_by-mauriciodmoura-blue">
  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/mauriciodmoura/dotnews">
  <a href="https://opensource.org/licenses/MIT">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-blue">
  </a>

</p>

---

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; &#xa0;  &#xa0;
</p>

<br>

## :dart: About ##

The .news platform is an exclusive blog that tailors content access based on a user's subscription status. Designed with an immersive user experience in mind, it boasts an integrated payment system powered by STRIPE. Once users complete their subscription payment, they gain unhindered access to the comprehensive content spread across the blog. Conversely, non-subscribers are granted a teaser view, with limited content access to whet their appetite.
<br>
To ensure data integrity and security, all vital information, including subscription verifications and user details, are securely stored within the FaunaDB database, a cutting-edge NoSQL database system.
<br>
One of the standout features of ig.news is its serverless architecture. In layman's terms, traditional backend processes have been ingeniously woven into the frontend, adhering to the JAMStack standards. This not only streamlines operations but also optimizes performance.
<br>
Content creation and management are a breeze, thanks to the integration with the Prismic CMS. Seamlessly connecting with the frontend, it ensures that every post reaches the audience in real-time. And with the potent combination of Next.js and React driving the platform's frontend, users are assured of a dynamic, responsive, and interactive browsing experience.
<br>
In essence, ig.news is a harmonious blend of modern technologies like Next, Prismic, React, Stripe, and NoSQL, offering users a premier blogging experience while maintaining operational efficiency and security.
<br>

## :rocket: Technologies ##

The following technologies were used in the project:

- [Next.js](https://nextjs.org/)
- [Prismic CMS](https://prismic.io/)
- [Stripe](https://stripe.com/)
- [FaunaDB](https://fauna.com/)

## :white_check_mark: Requirements ##

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/)

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/mauriciodmoura/dotnews

# Access
$ cd dotnews

# Install dependencies
$ yarn install

# Run the project
$ yarn dev

# The server will initialize in the <http://localhost:3000>
```




