

# STA 111: Introduction to Descriptive Statistics 📈

This repository contains a structured dataset of Multiple Choice Questions (MCQs) designed to aid students in mastering the fundamentals of descriptive statistics. The data is pre-formatted for seamless integration into web-based quiz engines and study tools.

## 🎓 About the Author

I am a **Computer Science with Economics student at Obafemi Awolowo University (OAU)**. By combining statistical theory with computational data structures, I aim to provide **Great Ife** students with high-quality, accessible digital study materials for the STA 111 curriculum.



## 🛠 Data Format

The dataset is organized as an array of JavaScript objects, making it "plug-and-play" for developers:

```javascript
{ 
  q: "What is the probability of an impossible event?", 
  o: ["1", "0.5", "0", "None of the above"], 
  a: "0" 
}

```

## 📖 Topics Covered

This repository covers the standard **OAU STA 111 syllabus**, including:

* **Descriptive Statistics:** Frequency distributions, histograms, ogives, and measures of central tendency (Mean, Median, Mode).
* **Measures of Dispersion:** Range, Variance, and Standard Deviation.
* **Counting Principles:** Permutations and Combinations.
* **Probability Theory:** Sample spaces, events, additive and multiplicative laws, and Conditional Probability.
* **Probability Distributions:** Introduction to the Binomial and Normal distributions.

## 🚀 How to Use

You can import this data directly into your JavaScript projects:

```javascript
// Example: Checking if a user's answer is correct
const isCorrect = (userChoice, questionIndex) => {
  return userChoice === sta111Data[questionIndex].a;
};

```

## 🤝 Contributing

Fellow **Great Ife** students are welcome to contribute! If you have verified past questions to add:

1. Fork this repository.
2. Add your questions using the established `{ q, o, a }` format.
3. Open a Pull Request.

---

**Curated with 📊 at OAU (Obafemi Awolowo University).**

