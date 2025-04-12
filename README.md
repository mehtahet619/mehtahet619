<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Het Chirag Mehta - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
    }
    .quote-container {
      margin-top: 20px;
      font-size: 1.2rem;
      background-color: #f9f9f9;
      padding: 20px;
      border-radius: 10px;
      border: 1px solid #ddd;
      max-width: 500px;
      margin: 0 auto;
    }
    #generate-quote {
      background-color: #38B2AC;
      color: white;
      padding: 10px 20px;
      font-size: 1rem;
      border: none;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 10px;
    }
    #generate-quote:hover {
      background-color: #319b8e;
    }
  </style>
</head>
<body>

  <h1 align="center">Hi there, I'm Het Chirag Mehta!</h1>
  <h3 align="center">AI/ML Developer | Full Stack Enthusiast | Ethical Hacking Enthusiast</h3>

  <p align="center">
    <a href="https://www.linkedin.com/in/het-mehta-5b9a47236" target="_blank">
      <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
    </a>
    <a href="https://hetmehtaportfolio.vercel.app/" target="_blank">
      <img src="https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
    </a>
  </p>

  <div class="quote-container" id="quote-container">
    <p id="quote-display">Click the button to get a random tech-related quote!</p>
    <button id="generate-quote">Generate Quote</button>
  </div>

  <script>
    const funnyQuotes = [
      "I told my AI to write a funny quote, but it just gave me a 404.",
      "AI: The new employee who never takes a vacation... or a coffee break.",
      "Why did the developer go broke? Because they used too many exceptions.",
      "My IoT devices are so smart, they’re the ones who tell me when I need a break!",
      "I tried to teach my AI to understand humor, but now it just does sarcastic data predictions.",
      "Full Stack Developer's diet: Coffee for breakfast, debugging for lunch, and more coffee for dinner.",
      "AI is like a toddler—cute, but you never know what it's going to do next.",
      "I asked my AI for a joke, and it gave me a 5-minute monologue on data ethics.",
      "Why did the AI break up with its algorithm? It found someone with better processing power.",
      "I tried explaining machine learning to my cat... now it’s demanding a training dataset.",
      "IoT devices are like kids—they always want your attention, but when you need them, they're offline.",
      "Debugging is like being a detective in a criminal movie where you are also the murderer.",
      "Full Stack Developer: because who needs sleep when you can fix bugs at 3 a.m.?",
      "AI is like a car—you’re never sure if it’s going to get you to your destination or take you on a detour.",
      "My machine learning model is so good, it already predicted I would get this joke.",
      "IoT: When your devices are smarter than your WiFi router.",
      "Why do programmers prefer dark mode? Because light attracts bugs.",
      "AI thinks it's the next big thing—until it tries to explain itself to a human.",
      "I gave my IoT devices a voice, and now they won’t stop arguing with each other.",
      "You can never have too many coffee breaks, but your code might say otherwise.",
      "The IoT fridge called. It’s tired of sending notifications about expired milk.",
      "Full Stack Developer's mood: 90% code, 10% coffee.",
      "My AI bot is learning humor, but it’s still stuck in the ‘dad joke’ phase.",
      "When the AI suggests a new feature, but you realize it doesn’t know what ‘user-friendly’ means.",
      "I thought my code was perfect... until it met the production server.",
      "Trying to teach an AI to make decisions is like asking a toddler to pick their favorite toy from a pile of 200.",
      "Why did the cybersecurity expert bring a ladder to work? To check the higher security levels.",
      "I don't always write code, but when I do, it compiles on the first try... said no developer ever.",
      "I asked my IoT device for help, and it responded with ‘Please reset and try again.’",
      "Machine learning models are like toddlers: they require constant supervision and tantrum management.",
      "Full Stack Developer life: When you’re at the front end but still dreaming about backend problems.",
      "I let my AI read all the data and now it’s writing a novel about how machines are the future.",
      "IoT devices should come with a warning: 'May attempt to invade your privacy when you're not looking.'",
      "Why did the AI fail at comedy? It kept overfitting the punchlines.",
      "My code runs perfectly... in my dreams.",
      "Cybersecurity: The art of not letting anyone else in while you’re still locked out.",
      "Full Stack Developer’s motto: You break it, I’ll fix it... eventually.",
      "I asked my chatbot to tell me a joke, but it responded with ‘Have you tried updating your system?’",
      "AI is like a genie: it grants wishes, but you better be specific.",
      "When your IoT device sends a notification, but it’s just to say it’s ‘too busy’ to function.",
      "Machine learning: When your algorithm knows more about you than your therapist.",
      "IoT security: because even your fridge needs a firewall now.",
      "If debugging is the process of removing bugs, then programming must be the process of putting them in.",
      "Full Stack Developer’s checklist: Fix the backend, break the frontend, fix the frontend, break the backend.",
      "I gave my AI a list of tasks, but it only returned a recursive function error.",
      "The best way to start learning AI is to let it teach you... until it starts charging you hourly.",
      "When IoT devices get together, it’s like a never-ending conference call with no agenda.",
      "My code works on my machine... but who am I kidding?",
      "Machine learning: Let’s hope the model doesn’t predict this sentence as a mistake.",
      "AI models are great until they start predicting your bad mood based on your coffee intake.",
      "Full Stack Developer's favorite programming language: Whatever gets the job done by deadline.",
      "My AI is great at playing chess... but it can’t figure out how to set an alarm for 7 AM.",
      "Cybersecurity is like a good password: Everyone knows it’s important, but no one wants to do it.",
      "Why do developers love the cloud? Because it’s just one big excuse for their code to go ‘up there’.",
      "I gave my IoT device a personality. Now it’s texting me more than my friends.",
      "Debugging in machine learning is just adding ‘print’ statements until it works.",
      "I tried explaining APIs to my cat, but now it’s sending me JSON instead of meowing."
    ];

    // Function to generate a random funny quote
    document.getElementById("generate-quote").onclick = function() {
      const randomIndex = Math.floor(Math.random() * funnyQuotes.length);
      document.getElementById("quote-display").innerText = funnyQuotes[randomIndex];
    };
  </script>

</body>
</html>
