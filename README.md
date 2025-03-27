<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,15,20,30&height=180&section=header&text=Dylan%20Lesieur&fontSize=42&fontAlignY=40&desc=System%20Optimization%20Specialist&descSize=22&descAlignY=65&animation=twinkling" width="100%"/>
</div>

<h3 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=00A8FF&center=true&vCenter=true&random=false&width=435&lines=C+Development+Expert;Performance+Optimization;Algorithm+Design;42+School+Student" alt="Typing SVG" />
</h3>

<!-- Social badges -->
<p align="center">
  <a href="https://www.linkedin.com/in/dylan-lesieur-1218aa1b1/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://puzzled-basil-cc8.notion.site/18352b5682188018accae57b55410ea8?v=18f52b56821880ffbb72000cea8f882f&pvs=4"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white"/></a>
  <a href="mailto:dylan.lesieur@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=LESdylan&style=for-the-badge&color=blue" alt="Profile views"/>
</p>

<!-- Snake animation -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg">
  </picture>
</div>

## About Me

<img align="right" width="300" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmQ1OTBjYzlkMWYxOTBhZGQyODUxNjE1ZGJlNTYyYmZkMjVlZjg0NyZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/qgQUggAC3Pfv687qPC/giphy.gif"/>

```c
typedef struct s_profile {
    char *name;
    char *location;
    char **specialties;
    char **current_learning;
} t_profile;

t_profile *create_profile(void) {
    t_profile *profile = malloc(sizeof(t_profile));
    
    profile->name = "Dylan Lesieur";
    profile->location = "42 School";
    profile->specialties = (char *[]){
        "Algorithm Optimization",
        "Low-level Programming",
        "Memory Management",
        "Performance Testing",
        NULL
    };
    profile->current_learning = (char *[]){
        "Advanced C Techniques",
        "System Architecture",
        "Linux Kernel Internals",
        NULL
    };
    
    return profile;
}
```

As a **low-level optimization specialist**, I'm dedicated to crafting efficient, elegant solutions to complex programming challenges. My work at 42 School has honed my ability to write clean, performant code with minimal resources.

I believe that understanding how things work at a fundamental level is essential for creating truly optimized software. Whether it's managing memory efficiently or designing algorithms with the lowest possible complexity, I'm driven to find the most elegant solution.

## Tech Stack

<div align="center">
  <h3>Core Languages & Tools</h3>
  <p>
    <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
    <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
    <img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"/>
    <img src="https://img.shields.io/badge/GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white"/>
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
    <img src="https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white"/>
    <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  </p>
  
  <h3>Development Skills</h3>
  <p>
    <img src="https://img.shields.io/badge/Algorithm_Design-4285F4?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Memory_Management-FF5722?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Performance_Testing-FFCA28?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Clean_Code-34A853?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Unit_Testing-7B68EE?style=for-the-badge"/>
  </p>
  
  <h3>Other Technologies</h3>
  <p>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
    <img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  </p>
</div>

## Testing & Optimization Philosophy

```bash
#!/bin/bash
# My optimization workflow

function optimize() {
  local code=$1
  
  echo "🔍 Analyzing $code"
  # Measure performance baseline
  baseline=$(benchmark "$code")
  
  echo "🧪 Running test suite"
  if ! run_tests "$code"; then
    echo "❌ Tests failed. Fix functionality first."
    return 1
  fi
  
  echo "📊 Identifying bottlenecks"
  bottlenecks=$(profile "$code")
  
  for bottleneck in $bottlenecks; do
    echo "♻️ Optimizing: $bottleneck"
    optimization_applied=$(apply_optimization "$code" "$bottleneck")
    
    echo "🔄 Testing optimized code"
    if ! run_tests "$optimization_applied"; then
      echo "⚠️ Optimization broke functionality. Reverting."
      continue
    fi
    
    new_perf=$(benchmark "$optimization_applied")
    improvement=$(calc_improvement "$baseline" "$new_perf")
    
    echo "📈 Performance improvement: $improvement%"
    if (( $(echo "$improvement > 5" | bc -l) )); then
      code=$optimization_applied
      baseline=$new_perf
    fi
  done
  
  echo "📝 Documenting optimizations"
  return 0
}
```

I approach software optimization methodically:

1. **Function first, speed second** - Ensure correctness before optimizing
2. **Measure, don't guess** - Use profiling to identify real bottlenecks
3. **Test every change** - Verify optimizations don't break functionality
4. **Document the process** - Record what worked and what didn't

## GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=LESdylan&theme=react&hide_border=true" width="400"/>
  <img src="https://github-readme-stats.vercel.app/api?username=LESdylan&show_icons=true&theme=react&hide_border=true&count_private=true" width="400"/>
</div>

## Featured Projects

<div align="center">
  <a href="https://github.com/Univers42/ft_printf_42">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Univers42&repo=ft_printf_42&theme=react&hide_border=true" />
  </a>
  <a href="https://github.com/Univers42/GetNextLine">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Univers42&repo=GetNextLine&theme=react&hide_border=true" />
  </a>
</div>

## Current Focus

I'm currently focused on:
- 📊 **Algorithmic Efficiency** - Reducing time complexity in critical operations
- 🧠 **Memory Optimization** - Minimizing memory usage without sacrificing performance
- 🔧 **Testing Methodology** - Building robust test frameworks to validate optimizations
- 📝 **Code Readability** - Ensuring optimized code remains maintainable

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Random dev quote" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,15,20,30&height=100&section=footer&animation=twinkling" width="100%"/>
</div>

<p align="right">Last updated: 2025-03-27</p>
