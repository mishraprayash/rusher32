
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Github Profile</title>
    <style>
      * {
        box-sizing: border-box;
      }
      .wrapper {
        width: 1000px;
        background-color: rgba(199, 229, 229, 0.482);
        margin: 0 auto;
      }
      .name-intro {
        letter-spacing: 3px;
        text-align: center;
        font-family: "Times New Roman", Times, serif;
        animation: color-transition ease-in-out infinite forwards
          alternate-reverse 2s;
          background-color: rgb(173, 211, 245);
          border-radius: 10px;
      }
      @keyframes color-transition {
        0% {
          color: rgb(101, 65, 65);
          /* background: linear-gradient(to right, rgb(180, 106, 106),rgb(82, 82, 50),rgbrgb(214, 76, 205)); */
        }
        33% {
          color: brown;
          /* background: linear-gradient(to right, rgb(235, 180, 180),rgb(116, 116, 106),rgb(89, 89, 106)); */
        }
        66% {
          color: rgb(135, 113, 77);
        }
        100% {
          color: rgba(66, 66, 219, 0.795);
        }
      }
      h2 {
        text-align: center;
        font-family: monospace;
        font-weight: bolder;
        font-size: 1.3rem;
        background: linear-gradient(to left, red,rgb(119, 119, 182),rgb(133, 168, 133),rgb(162, 162, 129),rgb(236, 178, 178));
        border-radius: 10px;
      }
      h3 {
        text-align: center;
        font-family: Georgia, "Times New Roman", Times, serif;
        letter-spacing: 2px;
        background-color: cadetblue;
        border-radius: 0.5rem;
      }
      h3:hover {
        text-decoration: underline;
      }
      .gifimage img{
        border-radius: 10px;
      }
      .profile-views-container {
        display: flex;
        justify-content: center;
      }
      .profile-views {
        border-radius: 10px;
      }
      .info-list {
        background-color: rgb(191, 232, 232);
        border-radius: 20px;
        text-align: center;
        list-style-type: none;
        font-family: monospace;
        font-weight: 900;
        transition: ease-in 0.2s;
        font-size: x-large;
      }
      .info-list span:hover {
        font-size: 1.1em;
        color: grey;
      }
      .connect-with-me {
        display: flex;
        justify-content: center;
        gap: 1rem;
        padding: 1rem;
        margin: 0.5rem;
      }
      .connect-with-me img:hover {
        transition: ease-in 0.2s;
      }
      .connect-with-me:hover img:hover {
        transform: scale(1.1);
        background-color: lightgray;
        border-radius: 0.5rem;
      }
      img {
        padding: 5px;
        margin: 5px;
      }
      .skills {
        display: flex;
        justify-content: center;
        padding: 0.5rem;
        margin: 0.5rem;
      }
      .skills img:hover {
        transition: ease-in 0.2s;
      }
      .skills:hover img:hover {
        transform: scale(1.1);
        background-color: lightgray;
        border-radius: 0.5rem;
      }
      .language-stats {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
      }
      .language-stats img {
        border-radius: 10px;
        background-color: lightblue;
        box-shadow: 1px 3px 1px 10px rgba(254, 255, 255, 0.482);
      }
      .language-stats img:hover {
        transition: 0.3s ease-in;
      }
      .language-stats:hover img:hover {
        transform: translate(0, 5px);
      }
    </style>
  </head>
  <body>
    <div class="wrapper">
      <h1 class="name-intro">Hi 👋, I'm Prayash Mishra</h1>
      <!-- <p><a href="mailto:mishraprayash11@gmail.com">Send email</a></p> -->
      <h2>
        A Computer Engineering student,an enthusiast and a passionate learner.
      </h2>
      <div class="gifimage" style="display: flex; justify-content: center">
        <img
          src="https://i.pinimg.com/originals/81/17/8b/81178b47a8598f0c81c4799f2cdd4057.gif"
          width="400px"
          alt="A gif "
        />
      </div>
      <p class="profile-views-container">
        <img
          class="profile-views"
          src="https://komarev.com/ghpvc/?username=rusher32&label=Profile%20views&color=0e75b6&style=flat"
          alt="rusher32"
        />
      </p>
      <ul class="info-list">
        <li>
          - 🔭 I’m currently working on **<span
            >Personal BLOG using NodeJs,Express and MongoDB</span
          >**.
        </li>
        <li>
          - 💬 Ask me about **<span
            >Javascript,Nodejs, Express,MongoDB and manymore</span
          >**.
        </li>
        <li>- 📫 How to reach me **<span>mishprayash00@gmail.com</span>**</li>
      </ul>
      <h3>Connect with me:</h3>
      <div class="connect-with-me">
        <a
          href="https://linkedin.com/in/https://www.linkedin.com/in/prayash-mishra-5a409422b/"
          target="blank"
          ><img
            src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg"
            alt="prayash-mishra-5a409422b/"
            height="50"
            width="50"
        /></a>
        <a
          href="https://www.codechef.com/users/https://www.codechef.com/users/mishraprayash0"
          target="blank"
          ><img
            src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codechef.svg"
            alt="mishraprayash0"
            height="50"
            width="50"
        /></a>
        <a
          href="https://codeforces.com/profile/https://codeforces.com/profile/hero321"
          target="blank"
          ><img
            src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codeforces.svg"
            alt="https://codeforces.com/profile/hero321"
            height="50"
            width="50"
        /></a>
      </div>

      <h3>Languages and Tools:</h3>
      <div class="skills">
        <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg"
            alt="bootstrap"
            width="50"
            height="50"
          />
        </a>
        <a
          href="https://www.cprogramming.com/"
          target="_blank"
          rel="noreferrer"
        >
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg"
            alt="c"
            width="50"
            height="50"
          />
        </a>
        <a
          href="https://www.w3schools.com/cpp/"
          target="_blank"
          rel="noreferrer"
        >
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg"
            alt="cplusplus"
            width="50"
            height="50"
          />
        </a>
        <a
          href="https://www.w3schools.com/css/"
          target="_blank"
          rel="noreferrer"
        >
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
            alt="css3"
            width="50"
            height="50"
          />
        </a>
        <a href="https://expressjs.com" target="_blank" rel="noreferrer">
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg"
            alt="express"
            width="50"
            height="50"
          />
        </a>
        <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
          <img
            src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg"
            alt="figma"
            width="50"
            height="50"
          />
        </a>
        <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
          <img
            src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg"
            alt="git"
            width="50"
            height="50"
          />
        </a>
        <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
            alt="html5"
            width="50"
            height="50"
          />
        </a>
        <a
          href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"
          target="_blank"
          rel="noreferrer"
        >
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
            alt="javascript"
            width="50"
            height="50"
          />
        </a>
        <a href="https://www.linux.org/" target="_blank" rel="noreferrer">
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg"
            alt="linux"
            width="50"
            height="50"
          />
        </a>
        <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg"
            alt="mongodb"
            width="50"
            height="50"
          />
        </a>
        <a href="https://nodejs.org" target="_blank" rel="noreferrer">
          <img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg"
            alt="nodejs"
            width="50"
            height="50"
          />
        </a>
        <a href="https://postman.com" target="_blank" rel="noreferrer">
          <img
            src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg"
            alt="postman"
            width="50"
            height="50"
          />
        </a>
      </div>

      <div class="language-stats">
        <img
          width="600"
          src="https://github-readme-stats.vercel.app/api/top-langs?username=rusher32&show_icons=true&locale=en&layout=compact"
          alt="rusher32"
        />
        &nbsp;
        <img
          width="600"
          src="https://github-readme-stats.vercel.app/api?username=rusher32&show_icons=true&locale=en"
          alt="rusher32"
        />
        <img
          width="600"
          src="https://github-readme-streak-stats.herokuapp.com/?user=rusher32&"
          alt="rusher32"
        />
      </div>
    </div>
  </body>
</html>
