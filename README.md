<header>
  <!--
    <<< Author notes: Course header >>>
    Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
    In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
    Add your open source license, GitHub uses MIT license.
  -->
  <h1>Yuchen Gong's Blog</h1>
  <p><em>yuchen4901@foxmail.com</em></p>
</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->
<section id="step2">
  <h2>Step 2: Configure your site</h2>
  <p>You turned on GitHub Pages! :tada:</p>
  <p>We'll work in a branch, <code>my-pages</code>, that I created for you to get this site looking great. :sparkle:</p>
  <p>Jekyll uses a file titled <code>_config.yml</code> to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the <code>_config.yml</code> file on the <strong>Code</strong> tab of your repository.</p>
  <p>We need to use a blog-ready theme. For this activity, we will use a theme named "minima".</p>
  
  <article>
    <h3>:keyboard: Activity: Configure your site</h3>
    <ol>
      <li>
        <p>Browse to the <code>_config.yml</code> file in the <code>my-pages</code> branch.</p>
      </li>
      <li>
        <p>In the upper right corner, open the file editor. This editor allows you to modify the content of the file easily. You can add, delete, or update the configuration settings here.</p>
      </li>
      <li>
        <p>Add a <code>theme:</code> set to <strong>minima</strong> so it shows in the <code>_config.yml</code> file as below:</p>
        <pre><code class="language-yml">
theme: minima
        </code></pre>
        <!-- This sets the theme of the Jekyll site to minima, which gives the site a predefined look and feel. -->
      </li>
      <li>
        <p>(optional) You can modify the other configuration variables such as <code>title:</code>, <code>author:</code>, and <code>description:</code> to further customize your site. These variables help define the identity and content of your site, making it more personalized.</p>
      </li>
      <li>
        <p>Commit your changes. Committing saves your modifications and makes them part of the branch's history, allowing you to track changes over time.</p>
      </li>
      <li>
        <p>(optional) Create a pull request to view all the changes you'll make throughout this course. Click the <strong>Pull Requests</strong> tab, click <strong>New pull request</strong>, set <code>base: main</code> and <code>compare:my-pages</code>. A pull request is a way to propose changes and merge them into the main branch after review, helping in collaborative development.</p>
      </li>
      <li>
        <p>Wait about 20 seconds then refresh this page (the one you're following instructions from). <a href="https://docs.github.com/en/actions">GitHub Actions</a> will automatically update to the next step. GitHub Actions is a powerful automation tool that can perform various tasks, like deploying your site or running tests, based on your configurations.</p>
      </li>
    </ol>
  </article>
</section>

<footer>
  <!--
    <<< Author notes: Footer >>>
    Add a link to get support, GitHub status page, code of conduct, license link.
  -->
  <hr>
  <p>For support, visit <a href="#">[Support Link]</a>. Check the <a href="#">GitHub Status Page</a> for service updates. Read our <a href="#">Code of Conduct</a> and <a href="#">License</a>.</p>
</footer>
