# WorkerCF


# Setup Steps
To get started, you need to register on Cloudflare.
Find the Worker section on the left sidebar and create a new project.
Then enter the edit code section and place the codes of the Worker.JS file. and saved.

> [!WARNING]
> Worker cloudflare has a limit of 100,000 requests per day.


# Expiry date feature 

> [!NOTE]
>  First, put the following two variables at the beginning of the code and set the expiration date.
> ```
> const targetH = "2026-12-30T00:00:00"
> const targetDate = new Date(targetH);
> ```
>  And put the following codes in line 240
> ```
>if (currentDate > targetDate) {
>
> userID = "None";
>
>} 
> ```

<p align="center">
  <a target="_blank" href="https://t.me/XuvixC">
    <img alt="Telegram Badge" src="https://img.shields.io/badge/XuVixChanel-Telegramlink?style=1&logo=telegram&logoColor=white&color=blue&link=https%3A%2F%2Ft.me%2FXuVix&link=https%3A%2F%2Ft.me%2FXuVix">
  </a>
