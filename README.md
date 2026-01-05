# 👋 Hello, I'm Talha! 
### 🚀 Frontend Developer & Multi-Language Programmer

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="Profile Banner" width="800" height="300">
</p>

## 🛠️ Tech Stack & Skills

### 💻 **Frontend Development**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### 🐍 **Backend & Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

### 🎯 **Currently Focused On**
<p align="center">
  <img src="https://media.giphy.com/media/XAxylRMCdpbEWUAvr8/giphy.gif" width="50" height="50">
  <img src="https://media.giphy.com/media/fsEaZldNC8A1PJ3mwp/giphy.gif" width="50" height="50">
  <img src="https://media.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif" width="50" height="50">
</p>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ithyb&show_icons=true&theme=radical&count_private=true&hide_border=true" alt="GitHub Stats">
  <br><br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ithyb&layout=compact&theme=radical&hide_border=true" alt="Top Languages">
  <br><br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ithyb&theme=radical&hide_border=true" alt="GitHub Streak">
</p>

## 🚀 Projects Showcase

### 🌐 **Frontend Projects**
- 🔹 **E-commerce Dashboard** - React + Tailwind CSS
- 🔹 **Portfolio Website** - Animated with GSAP
- 🔹 **Weather App** - JavaScript + API Integration

### 📱 **Mobile Apps**
- 🔸 **Todo App** - Flutter + Firebase
- 🔸 **Fitness Tracker** - React Native

### 🐍 **Python Projects**
- 🐼 **Data Analysis Tools** - Pandas + NumPy
- 🤖 **Automation Scripts** - Selenium + BeautifulSoup

## 📫 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/yourprofile">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://twitter.com/yourprofile">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="https://yourportfolio.com">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio">
  </a>
  <a href="mailto:youremail@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

## 💡 Featured Code Snippet

```javascript
// Animated greeting component
const ProfileGreeting = () => {
  const [greeting, setGreeting] = useState("Hello World!");
  
  useEffect(() => {
    const greetings = [
      "👋 Hi, I'm Talha!",
      "💻 Frontend Developer",
      "🐍 Python Enthusiast",
      "📱 Flutter Developer",
      "🚀 Building Amazing Apps"
    ];
    
    let i = 0;
    const interval = setInterval(() => {
      setGreeting(greetings[i]);
      i = (i + 1) % greetings.length;
    }, 2000);
    
    return () => clearInterval(interval);
  }, []);
  
  return (
    <div className="animated-greeting">
      <h1>{greeting}</h1>
    </div>
  );
};
