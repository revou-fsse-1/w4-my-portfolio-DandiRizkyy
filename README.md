## Dandi Rizky Week 4 Assignment (Deployment and Custom Domain Setup)

<img src="https://raw.githubusercontent.com/DandiRizkyy/slackmoji/master/emoji/blob/blob-wave-gif.gif" width="50px" height="50px" alt="hello">

## Description ✍🏻

---

<p> On this week assignments, i do some documentation on how to deploy website to netlify, cloudflare, buy domain at niagahoster and connect custom domain to netlify.

---

## Links 🔗

---

- Netlify Domain : https://dandirizkyy-week4-portofolio-website.netlify.app/
- Custom Domain : https://dandirizky.site

## Deployment Process 🔔

---

### 1. Sign Up to Netlify

- First of all, you need to sign up to netlify in order to configure and deploy your website.
  ![Netlify Signup](/assets/1.png)

### 2. Importing Project

- Second, you need to import your project from your github repository.
  ![Importing Project](/assets/2.png)
  ![Importing Project](/assets/3.png)

### 3. Choose Your Project

- Third, choose your project from your repository and click **Deploy Site !**
  ![Choosing Project](/assets/4.png)
  ![Choosing Project](/assets/5.png)
  ![Choosing Project](/assets/6.png)

### 4. And voila, Your Site Is Deployed and Live for Public !

- You could also change the site name whatever you want, but we're not done yet because the domain name still ended with **netlify.app**. To fix that we need to buy a new domain name from domain registrar, In the next steps i will show you how to buy a new domain name from NiagaHoster.
  ![Deployed](/assets/7.png)
  ![Deployed](/assets/8.png)
  ![Deployed](/assets/9.png)

## Buying Domain Name From NiagaHoster 💡

---

### 1. Go to NiagaHoster Website

- Hover your mouse to Domain and click **Cari & Cek Domain.** From there you can input your domain name (dot) site, and they will check it's **avaibility.** If it's **avaiable**, you can click **pilih.**
  ![Buying Domain Name](/assets/10.png)
  ![Buying Domain Name](/assets/11.png)

### 2. Finish The Payment Method

- You can use a lot of different payment methods here. Click **Lanjutkan** to finish the payment process.
  ![Buying Domain Name](/assets/12.png)

- Because i already bought the domain name before, after done the payment process, hover your mouse to **Layanan** and click **Layanan Saya**.
  ![Buying Domain Name](/assets/13.png)

- Andd voila ! you just bought a fresh Domain Names
  ![Buying Domain Name](/assets/14.png)

## Custom Domain Setup Process 📌

---

### 1. Setting up your Domain on Cloudflare

- After you bought your domain, go to cloudflare website, register and click **add site**
  ![Setup Domain](/assets/15.png)

- After that, enter your domain names and choose free plan.
  ![Setup Domain](/assets/16.png)
  ![Setup Domain](/assets/17.png)

- After choosing plan, click **add record**, **set type into CNAME**, **input @ and www**, **input netlify domain name** and **click save**
  ![Setup Domain](/assets/18.png)
  ![Setup Domain](/assets/19.png)

- Also dont forget to change the original **niagahoster nameservers** to **cloudflare nameservers** (the changing process could take up to 24 hours, so be patient.)
  ![Setup Domain](/assets/20.png)
  ![Setup Domain](/assets/21.png)

  Anddddd that's it ! The next step is Setting Custom Domain on Netlify.

### 2. Setting up Custom Domain to Netlify

- After you set your domain on cloudflare, go back to netlify and click **set custom domain**
  ![Setup Custom Domain Netlify](/assets/22.png)

- Enter your domain names, click **verify** and **add domain.**
  ![Setup Custom Domain Netlify](/assets/23.png)
  ![Setup Custom Domain Netlify](/assets/24.png)

## All set ! Your Website is Ready ! 🎊

---

![Setup Custom Domain Netlify](/assets/25.png)
![Setup Custom Domain Netlify](/assets/26.png)
