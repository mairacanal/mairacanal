```Rust
// ~/mairacanal.rs

impl AboutMe {
    fn getCurrentWorkplace() -> &str {
        "Igalia"
    }

    fn getCurrentDegree() -> Degree {
        Degree {
            course: "Computer Engineering",
            university: "University of São Paulo",
            onGoing: true,
        }
    }

    fn getDailyKnowledge() -> Vec<&str> {
        vec![
            "C/C++",
            "Rust",
            "Data Structures",
            "Linux Kernel",
            "Yocto",
            "FreeRTOS",
            "Computer Architecture",
            "Embedded Systems",
            "ARM",
            "Vim",
        ]
    }

    fn getOpenSourceProjects() -> Vec<&str> {
        vec![
            "Linux Kernel, especially the DRM subsystem",
            "igt-gpu-tools",
            "Mesa",
            "VK-GL-CTS",
            "LLVM",
            "meta-openembedded",
        ]
    }

    fn getMyLinks() -> Vec<&str> {
        vec![
            "https://www.linkedin.com/in/mairacanal/",
            "https://mairacanal.github.io/",
        ]
    }

    fn getFutureGoal() -> &str {
        "Learn more about RISC-V, Rust, and GPU architecture."
    }
}
```
