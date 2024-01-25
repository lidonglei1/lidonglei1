###     👋 Hello I'm Deal 👋 
####    📺welcome to my home 📺

# My ![Visitor Count](https://profile-counter.glitch.me/HwzLoveDz/count.svg) visitor

![Dusai's GitHub stats](https://github-readme-stats.vercel.app/api?username=stacklens)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=lidonglei1&layout=compact&langs_count=6)

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lidonglei1&theme=solarized_dark)



![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=lidonglei1&theme=solarized_dark) ![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=lidonglei1&theme=solarized_dark&utcOffset=8)

<!-- Include the library. -->
<script
  src="https://unpkg.com/github-calendar@latest/dist/github-calendar.min.js">
</script>

<!-- Optionally, include the theme (if you don't want to struggle to write the CSS) -->
<link
  rel="stylesheet"
  href="https://unpkg.com/github-calendar@latest/dist/github-calendar-responsive.css"
/>

<!-- Prepare a container for your calendar. -->
<div class="calendar">
    <!-- Loading stuff -->
    Loading the data just for you.
</div>

<script>
    GitHubCalendar(".calendar", "your-username");

    // or enable responsive functionality:
    GitHubCalendar(".calendar", "your-username", { responsive: true });

    // Use a proxy
    GitHubCalendar(".calendar", "your-username", {
       proxy (username) {
         return fetch(`https://your-proxy.com/github?user=${username}`)
       }
    }).then(r => r.text())
</script>
