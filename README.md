# PROJECT2
PROJECT2
<!DOCTYPE html>
<html lang="en"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <title>Hacktoberfest presented by DigitalOcean</title>
    <meta charset="utf-8">
    <meta name="title" content="Hacktoberfest presented by DigitalOcean">
    <meta name="description" content="Open source is changing the world – one pull request at a time.">

    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:site" content="@hacktoberfest">
    <meta name="twitter:creator" content="@hacktoberfest">
    <meta name="twitter:title" content="Hacktoberfest presented by DigitalOcean">
    <meta name="twitter:description" content="Open source is changing the world – one pull request at a time.">
    <meta name="twitter:image" content="https://hacktoberfest.digitalocean.com/assets/og-hf20-cf92d1a3bfc78883ea79dbac1518f1a4f1585e23eb69337ea730447cb70fa777.png">
    <meta name="twitter:url" content="https://hacktoberfest.digitalocean.com/">

    <meta prefix="og: http://ogp.me/ns#" property="og:title" content="Hacktoberfest presented by DigitalOcean">
    <meta prefix="og: http://ogp.me/ns#" property="og:type" content="website">
    <meta prefix="og: http://ogp.me/ns#" property="og:locale" content="en_US">
    <meta prefix="og: http://ogp.me/ns#" property="og:site_name" content="Hacktoberfest">
    <meta prefix="og: http://ogp.me/ns#" property="og:description" content="Open source is changing the world – one pull request at a time.">
    <meta prefix="og: http://ogp.me/ns#" property="og:url" content="https://hacktoberfest.digitalocean.com/">
    <meta prefix="og: http://ogp.me/ns#" property="og:image" content="https://hacktoberfest.digitalocean.com/assets/og-hf20-cf92d1a3bfc78883ea79dbac1518f1a4f1585e23eb69337ea730447cb70fa777.png">

    <script async="" src="Hacktoberfest%20presented%20by%20DigitalOcean_files/gtm.js"></script><script type="text/javascript" async="" src="Hacktoberfest%20presented%20by%20DigitalOcean_files/analytics.js"></script><script type="text/javascript">
    
    // before turbolinks renders remove or add class dark - this is needed to prevent a flash of previous styles
    document.addEventListener("turbolinks:before-render", (event)=> {
      if (localStorage.getItem('mode') === 'light') event.data.newBody.classList.remove('dark')
      if (localStorage.getItem('mode') === 'dark')  event.data.newBody.classList.add('dark')
    })

    // after turbolinks fully loads readd or remove class dark - this is needed because turbolinks strips all scripts :/
    document.addEventListener("turbolinks:load", ()=> {
      ((localStorage.getItem('mode') || 'light') === 'dark') ? document.querySelector('body').classList.add('dark') : document.querySelector('body').classList.remove('dark');
    });
    </script>
    
    <link rel="shortcut icon" type="image/x-icon" href="https://hacktoberfest.digitalocean.com/assets/favicon-79cf6800e5106ab81f2e1d8b0d8aec638a803ced6d8d61539841b9754573e0f0.png">
    <meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="UaOJdZjsyu8LcmKaMKTZ0YHsPXqsOtzDfA7f71F6/sfZiMNoaCnagLVogKN5Z1tfbPZGuvUaEQz4rRfdkbGA6A==">
    
    <meta name="viewport" content="initial-scale=1.0, width=device-width">
    <link rel="stylesheet" media="all" href="Hacktoberfest%20presented%20by%20DigitalOcean_files/application-bc35a3d03bf22ea071add2320415f741f0e7d76ed41d2b01.css" data-turbolinks-track="reload">
    <link rel="stylesheet" href="Hacktoberfest%20presented%20by%20DigitalOcean_files/cookieConsent.css">
    <script src="Hacktoberfest%20presented%20by%20DigitalOcean_files/application-90c17c0b04559eeb63d0be1a0840a400cd5336652c66aa787.js"></script>
    <script>
  var airbrake = new airbrakeJs.Client({
    projectId: "244344",
    projectKey: "706287fc6c288d10169d2a8d38577941"
  });

  airbrake.addFilter(function(notice) {
    notice.context.environment = "production-js";
    return notice;
  });
</script>
    <script>
    !function(){var analytics=window.analytics=window.analytics||[];if(!analytics.initialize)if(analytics.invoked)window.console&&console.error&&console.error("Segment snippet included twice.");else{analytics.invoked=!0;analytics.methods=["trackSubmit","trackClick","trackLink","trackForm","pageview","identify","reset","group","track","ready","alias","debug","page","once","off","on"];analytics.factory=function(t){return function(){var e=Array.prototype.slice.call(arguments);e.unshift(t);analytics.push(e);return analytics}};for(var t=0;t<analytics.methods.length;t++){var e=analytics.methods[t];analytics[e]=analytics.factory(e)}analytics.load=function(t,e){var n=document.createElement("script");n.type="text/javascript";n.async=!0;n.src="https://cdn.segment.com/analytics.js/v1/"+t+"/analytics.min.js";var a=document.getElementsByTagName("script")[0];a.parentNode.insertBefore(n,a);analytics._loadOptions=e};analytics.SNIPPET_VERSION="4.1.0";
    analytics.load('on5tkWRozncTh5P5dyA1cVsyrkGgvpvU', (document.cookie.indexOf('cookieconsent_status=dismiss') > -1 ? {} : { integrations: { All: false, 'Segment.io': true}}));
    analytics.page();
    }}();
</script>

  <script src="Hacktoberfest%20presented%20by%20DigitalOcean_files/l.js"></script></head>
  <body class="dark">
  <div>
    <header>
  <nav class="navbar" id="navbar">
    <div class="navbar-primary">
      <a href="https://hacktoberfest.digitalocean.com/" class="logo">
        <img alt="Hacktoberfest Logo" class="nav-logo">
      </a>
      <ul class="navbar-links">
        <li><a class=" navLink" href="https://hacktoberfest.digitalocean.com/">home</a></li>
        <li><a class=" navLink" href="https://hacktoberfest.digitalocean.com/details">resources</a></li>
        <li class="dropdown is-hoverable">
          <div class="dropdown-trigger">
            <a class=" navLink" href="https://hacktoberfest.digitalocean.com/events">
              Events
              <small>▼</small>
</a>          </div>
          <div class="dropdown-menu" id="dropdown-menu" role="menu">
            <div class="dropdown-content">
              <a class="dropdown-item navLink" href="https://hacktoberfest.digitalocean.com/events">View All Events</a>
              <hr class="dropdown-divider">
              <a class="dropdown-item navLink" href="https://hacktoberfest.digitalocean.com/eventkit">Event Organizer Kit</a>
            </div>
          </div>
        </li>
        <li><a class=" navLink" href="https://hacktoberfest.digitalocean.com/faq">faq</a></li>
        <li>
            <a class="active navLink" href="https://hacktoberfest.digitalocean.com/profile">profile</a>
        </li>
      </ul>
    </div>
    <div class="toggle">
      <p>Dark Mode </p>
      <label class="toggle-switch">
        <input id="toggle-checkbox" type="checkbox" onclick="
            localStorage.setItem('mode', (localStorage.getItem('mode') || 'light') === 'light' ? 'dark' : 'light'); 
            localStorage.getItem('mode') === 'dark' ? document.querySelector('body').classList.add('dark') : document.querySelector('body').classList.remove('dark');
            " title="Dark/light" checked="checked">
          <span class="toggle-slider"></span>
      </label>
    </div>
  </nav>
</header>
<script>
// after turbolinks finishes loading check localStorage mode and check the toggle if it needs to be darkmode
document.addEventListener("turbolinks:load", ()=> {
  if(localStorage.getItem('mode') === 'dark') document.getElementById('toggle-checkbox').checked = true
});
</script>

    <div class="profile-page">
  <div class="profile-left">
    <div class="main-content-wrapper">
      <div class="account-wrapper">
        <span>
          <div class="avatar">
            <figure class="image">
              <img class="is-rounded" src="Hacktoberfest%20presented%20by%20DigitalOcean_files/andianipputri.jpg">
            </figure>
          </div>
          <h2 class="username title is-2">andianipputri </h2>
        </span>
        <div class="logout-wrapper">
          <a class="logout" href="https://hacktoberfest.digitalocean.com/logout">Log out @andianipputri</a>
        </div>
      </div>

      <div class="progress-wrapper mobile">
        <h4 class="progress-header">your progress</h4>
        <div class="pr-score">1 of 4 pull requests</div>
<div class="progress-bar progress-state-1">
  <div class="progress-block"></div>
  <div class="progress-block"></div>
  <div class="progress-block"></div>
  <div class="progress-block"></div>
</div>

      </div>


      <div class="hacktoberfest-results-box">
      </div>
      <div class="container">
        <div class="timeline-container">
    <h3 class="title is-3">Your contributions</h3><br>
    <table class="is-narrow is-fullwidth">
      <tbody>
          <tr>
  <td>
    <div class="timeline-wrapper">
      <div class="pr-icon">
          <div class="icon-box">
    <div class="pending-box">
    </div>
  </div>

      </div>
      <div class="pr-time-title">
        <div class="timeline-date">
          <p class="date">October 01, 2020 08:02<br></p>
        </div>
        <h4 class="pr-title">
          You submitted <a href="https://github.com/andianipputri/PROJECT-1/pull/1">2</a> to andianipputri/PROJECT-1<br>
        </h4>
      </div>
      <div class="pr-waiting">
          <span class="mature">mature in:</span> <span class="count-down" id="MDExOlB1bGxSZXF1ZXN0NDk2MDU0MjE2-waiting-date">6d:23h:57m:26s</span>
      </div>
    </div>
  </td>
</tr>

  <script type="text/javascript">
      countdownTimers(
          document.getElementById('MDExOlB1bGxSZXF1ZXN0NDk2MDU0MjE2-waiting-date'),
          "Thu, 01 Oct 2020 08:02:56 GMT",
      );
  </script>




      </tbody>
    </table>

    <div class="legend has-text-white">
      <h4 class="title is-4">Legend</h4>
      <div class="legend-container">
        <div class="icon-box">
          <div class="pending-box">
          </div>
        </div>
        <div class="icon-name-desc">
          <div class="icon-name">
            Pending
          </div>
          <div class="icon-desc">
            Your PR is currently within the review period, which lasts for seven days.
          </div>
        </div>
      </div>
      <div class="legend-container">
        <div class="icon-box">
          <div class="invalid-box">
          </div>
        </div>
        <div class="icon-name-desc">
          <div class="icon-name">
            Invalid
          </div>
          <div class="icon-desc">
            Your PR has been labeled as "invalid" or "spam" by a maintainer and won't count toward winning Hacktoberfest.
          </div>
        </div>
      </div>
      <div class="legend-container">
        <div class="icon-box">
          <div class="spammy-box">
          </div>
        </div>
        <div class="icon-name-desc">
          <div class="icon-name">
            Ineligible Repository
          </div>
          <div class="icon-desc">
            Your PR was submitted to a repository that we've excluded 
from Hacktoberfest as it doesn't align with our core values.
          </div>
        </div>
      </div>
      <div class="legend-container">
        <div class="icon-box">
          <div class="eligible-box">
          </div>
        </div>
        <div class="icon-name-desc">
          <div class="icon-name">
            Eligible
          </div>
          <div class="icon-desc">
            Good job! Your PR has passed the review period and counts toward completing the Hacktoberfest challenge!
          </div>
        </div>
      </div>
    </div>
</div>

      </div>
    </div>

    <div class="main-content-wrapper">
      <p>Have you seen a repository that you don't think aligns with the <a href="https://hacktoberfest.digitalocean.com/details">Hacktoberfest values</a>? Please <a href="https://hacktoberfest.digitalocean.com/report">report it to us</a> so we can take a look.</p>
    </div>
  </div>

  <div class="profile-right">
    <div class="progress-wrapper desktop">
      <h4 class="progress-header">your progress</h4>
      <div class="pr-score">1 of 4 pull requests</div>
<div class="progress-bar progress-state-1">
  <div class="progress-block"></div>
  <div class="progress-block"></div>
  <div class="progress-block"></div>
  <div class="progress-block"></div>
</div>

    </div>
    <div class="education-wrapper">
      <h4 class="side-headers">education hub</h4>
      <div class="education-section">
        <h5>Educate Yourself</h5>
        <ul>
          <li><a href="https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source" target="_blank">Get An Introduction to Open Source</a></li>
          <li><a href="https://hacktoberfest.digitalocean.com/details/" target="_blank">Digest the Resources</a></li>
          <li><a href="https://hacktoberfest.digitalocean.com/faq/" target="_blank">Get Answers Before Asking</a></li>
          <li><a href="https://www.digitalocean.com/community/tutorials/how-to-maintain-open-source-software-projects" target="_blank">Learn About Maintainer Experience</a></li>
          <li><a href="https://raise.dev/hacktoberfest" target="_blank">Get help from the Helpdesk</a></li>
        </ul>
      </div>
      <div class="education-section">
        <h5>Make An Impact</h5>
        <ul>
          <li><a href="https://hacktoberfest.digitalocean.com/eventkit/" target="_blank">Organize a Hacktoberfest Meetup</a></li>
          <li><a href="https://www.digitalocean.com/community/meetup_kits/hacktoberfest-workshop-kit-how-to-submit-your-first-pull-request-on-github" target="_blank">Lead an Open Source Workshop</a></li>
          <li><a href="https://dev.to/" target="_blank">Share Your Experience on DEV</a></li>
          <li><a href="https://raise.dev/hacktoberfest" target="_blank">Answer questions on the Helpdesk</a></li>
        </ul>
      </div>
    </div>

  </div>

</div>

  </div>
  <footer class="footer">
      <div class="footer-wrapper">
      <div class="do-logo">
        <a href="https://www.digitalocean.com/">
          <img alt="DigitalOcean Logo" class="footer-do-logo">
        </a>
      </div>

      <div class="footer-details">
        <p class="footer-p">
          © 2020 DigitalOcean, LLC. All rights reserved.
        </p>
        <ul class="footer-links">
          <li>
            <a href="https://www.digitalocean.com/legal/terms-of-service-agreement/">
              Terms
            </a>
          </li>
          <li>
            <a href="https://www.digitalocean.com/legal/privacy-policy/">
              Privacy
            </a>
          </li>
          <li>
            <a href="https://do.co/hacktoberbrand">
              Brand Guidelines
            </a>
          </li>
          <li>
            <a href="https://twitter.com/hacktoberfest">
              <img alt="Twitter" class="footer-twitter">
            </a>
            <a href="https://www.instagram.com/hacktoberfest/">
              <img alt="Instagram" class="footer-instagram">
            </a>
            <a href="https://discord.gg/hacktoberfest">
              <img alt="Discord" class="footer-discord">
            </a>
          </li>
        </ul>
      </div>
    </div>
</footer>


    <script type="text/javascript">
      window.cookieDomain = ".digitalocean.com";
    </script>

  <script src="Hacktoberfest%20presented%20by%20DigitalOcean_files/cookieConsent.js"></script>

    <script>
      window.addEventListener('cookieconsent_statuschange', function(e) {
        if(e.detail.status === 'deny') { return; }
        (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
        new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
        j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
        '//www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
        })(window,document,'script','dataLayer','GTM-KHWBBT');
      });
    </script>
  

<script type="text/javascript" id="">function getCookie(d){d+="\x3d";var b=decodeURIComponent(document.cookie);b=b.split(";");for(var c=0;c<b.length;c++){for(var a=b[c];" "==a.charAt(0);)a=a.substring(1);if(0==a.indexOf(d))return a.substring(d.length,a.length)}return""}function setCookie(d,b,c){var a=new Date;a.setTime(a.getTime()+6E4*c);document.cookie=d+"\x3d"+escape(b)+(null==c?"":";expires\x3d"+a.toGMTString())}
if(""==getCookie("sessionID")){var randomNumberString=Math.floor(1E7*Math.random()+1).toString();setCookie("sessionID",randomNumberString,30)}else{var sessionID=getCookie("sessionID");setCookie("sessionID",sessionID,30)};</script><iframe style="position:absolute;left:-999px;top:-999px;visibility:hidden"></iframe></body></html>
