# Infrastructure Engineer

<!-- Responsive terminal display -->
<picture>
  <source media="(min-width: 768px)" srcset="./assets/vim_editor_desktop.svg">
  <source media="(max-width: 767px)" srcset="./assets/vim_editor_mobile.svg">
  <img alt="Infrastructure Engineer Terminal" src="./assets/vim_editor_desktop.svg" width="100%">
</picture>

## About

<div align="center">

**Software Engineer → Infrastructure Engineer → [Available for Hire](./assets/arturo-builds-infra-resume.pdf)**

</div>

<details>
<summary><strong>TL;DR Profile</strong></summary>

```go
type InfrastructureEngineer struct {
    Name       string  // "infraturo"
    Role       string  // "Infrastructure Engineer"
    Since      int     // 2008 (16+ years)
    Transition int     // 2016 (software → infrastructure)
    Status     string  // "available_for_hire"
    Location   string  // "remote"
    
    Environment struct {
        OS       string // "linux"
        Editor   string // "vim"
        Terminal string // "foot + tmux + tiling-wm"
        Shell    string // "bash/zsh"
        Attitude string // "cli-over-gui"
    }
}
```

</details>

<details>
<summary><strong>Resume</strong></summary>

<!-- RESUME_START -->
<br>

**PROFESSIONAL SUMMARY**

Senior Site Reliability & Infrastructure Engineer with 7+ years of experience building scalable, high-uptime cloud infrastructure. Proven track record in 24/7 production on-call environments, architecting automation frameworks, and eliminating operational overhead. Expert in AWS/GCP, Kubernetes, and GenAI-driven automation, with a deep focus on system reliability and incident response.

**PROFESSIONAL EXPERIENCE**

**Platform Science** \- San Diego, CA  
*June 2019 \- Present*

***Senior Infrastructure Engineer**  |  April 2024 \- Present*  
***Infrastructure Engineer**  |  October 2021 \- April 2024*  
***Software Development Engineer**  |  June 2019 \- October 2021*

* Spearheaded integration of GenAI-driven automation (Claude Code, n8n) into infrastructure workflows, reducing request-to-completion time for environment provisioning by 80%  
* Participated in a 24/7 on-call rotation using PagerDuty for 4+ years, leading incident response for high-severity outages and conducting blameless post-mortems to improve system resilience and maintain high uptime  
* Architected custom GitOps framework for Kubernetes using ArgoCD plugin with gomplate templating \- automating deployment of core infrastructure components across 8 production clusters with automatic cluster discovery, eliminating manual bootstrapping processes and enabling zero-touch provisioning of new clusters  
* Engineered automated blue/green RDS migration system to bypass AWS in-place storage limitations, incorporating intelligent sizing calculations based on storage delta analysis, cross-team dependency management (parameter groups, binlog retention), and table optimization via ALTER operations \- reducing manual overhead from 8 hours to 45 minutes per instance and saving \~$100K annually across first two deployment groups  
* Led cross-functional cache optimization initiative to address recurring memory incidents (90%+ utilization), auditing TTL strategies and data retention policies across teams \- rightsizing ElastiCache instances to optimal capacity utilization and reducing annual costs by $15K while improving system stability  
* Built and maintained Terraform infrastructure-as-code modules for multi-cloud environments (AWS, GCP, Azure), enabling consistent provisioning patterns and reducing deployment errors across engineering teams  
* Designed and implemented comprehensive observability stack using Prometheus, Loki, and Grafana for Kubernetes monitoring, providing real-time visibility into cluster health and application performance  
* Developed CI/CD automation pipelines using GitHub Actions and Jenkins, streamlining deployment workflows and reducing time-to-production for infrastructure changes

**TECHNICAL SKILLS**

**Cloud & Orchestration:** AWS (primary), GCP, Azure, Kubernetes, Docker, ArgoCD, Flux CD, Helm  
**Infrastructure as Code:** Terraform, CloudFormation, GitOps  
**GenAI & Automation:** Claude Code, n8n, GitHub Actions, Jenkins, Python, Bash  
**Observability & Networking:** Prometheus, Grafana, PagerDuty (On-call), TCP/IP, DNS, TLS/SSL, ALB/NLB, AWS WAF, Route53  
**Databases:** RDS (MySQL, PostgreSQL), ElastiCache (Redis)  
**Development:** Python, PHP, JavaScript, RESTful APIs, Linux Administration

**EDUCATION**  
**Platt College San Diego**  
B.S. in Media Arts  *|  2004 \- 2008*

* Specialized degree in Web Design  
* Specialized degree in Digital Video Production
<!-- RESUME_END -->

[View / Download PDF](./assets/arturo-builds-infra-resume.pdf)

</details>

<details>
<summary><strong>Skills & Tech Stack</strong></summary>

```go
type Skills struct {
    // Container Orchestration
    Orchestration []string{
        "kubernetes", "docker", "helm",
    }
    
    // Infrastructure as Code
    IaC []string{"terraform"}
    
    // Cloud Platforms
    Cloud []string{"aws", "gcp", "azure"}
    
    // CI/CD & Automation
    Automation []string{
        "github-actions", "jenkins", "gitlab-ci",
    }
    
    // Monitoring & Observability
    Monitoring []string{
        "prometheus", "grafana", "datadog",
    }
    
    // Programming Languages
    Languages []string{
        "go", "python", "bash", "yaml",
    }
}
```

</details>

<details>
<summary><strong>Current Focus & Philosophy</strong></summary>

```go
type Focus struct {
    CurrentProjects []string{
        "platform-engineering",
        "developer-experience", 
        "gitops-workflows",
        "infrastructure-as-code",
    }
    
    Philosophy []string{
        "linux-is-life",
        "vim-keybindings-everywhere",
        "terminal-over-gui",
        "automation-over-manual-processes",
        "infrastructure-should-be-code",
    }
    
    UniqueValue string // "Software engineering mindset 
                      //  applied to infrastructure challenges"
}
```

</details>

<details>
<summary><strong>Complete Implementation</strong></summary>

<div style="overflow-x: auto;">

```go
package main

import (
    "fmt"
    "time"
)

type InfrastructureEngineer struct {
    Name                     string
    Role                     string
    SoftwareExperience       time.Duration
    InfrastructureExperience time.Duration
    Background               string
    Status                   string
    Location                 string
    Environment              Environment
    Skills                   Skills
    CurrentFocus             []string
    Philosophy               []string
    Dotfiles                 []string
}

type Environment struct {
    OS           string
    Editor       string
    Terminal     string
    Shell        string
    Attitude     string
}

type Skills struct {
    Orchestration []string
    IaC          []string
    Cloud        []string
    Automation   []string
    Monitoring   []string
    Languages    []string
}

func NewInfraturo() *InfrastructureEngineer {
    return &InfrastructureEngineer{
        Name:                     "infraturo",
        Role:                     "Infrastructure Engineer",
        SoftwareExperience:       time.Hour * 24 * 365 * 16, // Since 2008
        InfrastructureExperience: time.Hour * 24 * 365 * 8,  // Transitioned ~2016
        Background:               "software-engineer-turned-ops",
        Status:                   "available_for_hire",
        Location:                 "remote",
        
        Environment: Environment{
            OS:       "linux",                    // The only real choice
            Editor:   "vim",                      // Because efficiency matters
            Terminal: "foot + tmux + tiling-wm",  // Peak productivity setup
            Shell:    "bash/zsh",                 // Home sweet home
            Attitude: "cli-over-gui",             // Command line supremacy
        },
        
        Skills: Skills{
            Orchestration: []string{"kubernetes", "docker", "helm"},
            IaC:          []string{"terraform"},
            Cloud:        []string{"aws", "gcp", "azure"},
            Automation:   []string{"github-actions", "jenkins", "gitlab-ci"},
            Monitoring:   []string{"prometheus", "grafana", "datadog"},
            Languages:    []string{"go", "python", "bash", "yaml"},
        },
        
        CurrentFocus: []string{
            "platform-engineering",
            "developer-experience",
            "gitops-workflows",
            "infrastructure-as-code",
        },
        
        Philosophy: []string{
            "linux-is-life",
            "vim-keybindings-everywhere",
            "terminal-over-gui",
            "automation-over-manual-processes",
            "infrastructure-should-be-code",
        },
        
        Dotfiles: []string{
            "gitlab.com/wd2nf8gqct/dotfiles.bootstrap", // Machine bootstrap
            "gitlab.com/wd2nf8gqct/dotfiles.core",      // Core system configs
            "gitlab.com/wd2nf8gqct/dotfiles.di",        // Desktop integration
            "gitlab.com/wd2nf8gqct/dotfiles.nix",       // NixOS configuration
        },
    }
}

func (ie *InfrastructureEngineer) GetContactInfo() map[string]string {
    return map[string]string{
        "github":   "github.com/arturo-builds-infra",
        "linkedin": "linkedin.com/in/arturo-builds-infra",
    }
}

func (ie *InfrastructureEngineer) GetUniqueValue() string {
    return "Software engineering mindset applied to infrastructure challenges"
}

func main() {
    engineer := NewInfraturo()
    
    fmt.Printf("// %s - %s\n", engineer.Name, engineer.Role)
    fmt.Printf("// %s\n", engineer.GetUniqueValue())
    fmt.Printf("// Since 2008: Software → Infrastructure\n")
    fmt.Printf("// foot + tmux + tiling WM = peak productivity\n\n")
    
    if engineer.Status == "available_for_hire" {
        fmt.Println("Ready for new challenges")
    }
}
```

</div>
</details>

## What I Do

**Infrastructure as Code** - Everything versioned, reviewed, and deployed through code  
**Kubernetes Orchestration** - Container workloads at scale  
**Multi-Cloud Architecture** - AWS, GCP, Azure expertise  
**GitOps Workflows** - Git as the single source of truth  
**Observability** - Prometheus, Grafana, and comprehensive monitoring  

## My Journey

Started as a software engineer in **2008**, building applications and learning the craft of code. Around **2016**, I transitioned into infrastructure and operations, bringing my development background with me.

This unique perspective means I:
- Write infrastructure like software (testing, versioning, CI/CD)
- Understand developer pain points and optimize for DX
- Bridge the gap between dev and ops teams
- Automate everything that can be automated

## Working Style

**Linux Native** - Ubuntu, CentOS, Alpine... if it runs in production, I'm comfortable with it  
**Vim Enthusiast** - hjkl navigation is muscle memory. Can make do with Mac when required, but let's be real - we're infrastructure people working on Linux machines  
**foot + tmux + tiling WM** - Peak terminal productivity setup. Session persistence, window management, zero mouse dependency  
**Keyboard Driven** - Why reach for a mouse when Super+hjkl gets you anywhere? Tiling window managers just make sense  
**CLI First** - If there's not a command-line tool for it, I'll probably write one  

## Dotfiles & Configs

A fully reproducible environment treated like infrastructure — versioned, automated, and ready to deploy on a fresh machine.

**[Bootstrap](https://gitlab.com/wd2nf8gqct/dotfiles.bootstrap)** - Provisions a new machine from scratch: package installation, system defaults, and dotfile wiring  
**[Core Configs](https://gitlab.com/wd2nf8gqct/dotfiles.core)** - Shell setup, editor config, and the utilities that make a terminal feel like home  
**[Desktop Integration](https://gitlab.com/wd2nf8gqct/dotfiles.di)** - Window manager, terminal, and desktop environment configuration  
**[NixOS](https://gitlab.com/wd2nf8gqct/dotfiles.nix)** - NixOS flake configuration for declarative, reproducible system and home management

## Currently

**Exploring**: Platform engineering, developer experience improvements  
**Status**: Available for consulting and full-time opportunities  
**Location**: Remote-first, Washington DC Area  

---

<div align="center">

**Let's build something amazing together**

[GitHub](https://github.com/arturo-builds-infra) • [LinkedIn](https://www.linkedin.com/in/arturo-builds-infra/) • [Resume](./assets/arturo-builds-infra-resume.pdf)

</div>
