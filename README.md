# Prosper Social Finance

A new website for Prosper Social Finance.

## Accessing the CMS

You can access the CMS at [prospersocialfinance.co.uk/admin](https://prospersocialfinance.co.uk/admin)

You will need to log in with the credentials you created when we set this up. If you have forgotten your login details, contact [ryanschuller@gmail.com](mailto:ryanschuller@gmail.com) and I can send you a password reset email.

Through the CMS you can add blog pages as well as add and edit all the main content pages. There are tutorials for doing this online if you search for "Netlify CMS" or you can get in touch for help.

## Editing the management team page

When editing the management team page you will see some of the content is in HTML as below.

```
<div class="team-member">
    <div class="team-image-container">
        <img class="team-image" src="/images/team/vicky-grant.jpeg">
        <a href="https://www.linkedin.com/in/vicky-grant-669280195/">
            <div class="linkedin-holder">
                <i class="linkedin-icon fa fa-linkedin"></i>
            </div>
        </a>
    </div>
    <div class="team-info-container">
        <h3 class="team-member-name">Vicky Grant</h3>
        <h5 class="team-member-position">Executive Director</h5>
        <p>"I am a fourth year Economics and Politics student. Growing up in Greece, I developed mixed feelings about finance but coming to university I knew it was a discipline I wanted to explore. Prosper was the ideal way to do this. It not only challenged my perception of finance, it also taught me how to use technical skills to deliver positive social impact. I am excited to lead Prosper in this new chapter and help expand its reach to students and social enterprises.”</p>
    </div>
</div>
```

You only need to swap out the:
- Image name (after yoy have uploaded one)
- LinkedIn link
- Name
- Bio paragraph

If you wish to create a new team member, simply copy and paste the snippet above and edit the specified details plus their position title. Similarly, to delete a team member simply delete the relevant snippet as seen above.

## Editing the site code

This site was built in [Hugo](https://gohugo.io/). I recommend reading up on the [getting started](https://gohugo.io/getting-started/quick-start/) documentation if you haven't used it before.

The latest version of Hugo as of writing this is v0.74.3

Once you have installed Hugo and cloned the repository, you can run the site on a local server by running:

`hugo server`
