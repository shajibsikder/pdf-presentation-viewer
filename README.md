# HTML5 PDF Presentation Viewer - CyberDeck Framework

An open-source, hardware-accelerated, terminal-styled dynamic web presentation ecosystem. Built specifically for students, teachers, colleges, seminars, and classrooms to deliver crisp 4K projector presentations with asynchronous memory management and real-time remote PDF loading.

* **Live Tool Link:** [Launch Live CyberDeck Terminal](https://s3.shajib.my.id/)
* **Licensing:** Free / Open Source (MIT License)

---

## Technical Architecture & Core Vendor Profile

### Engineering Overview
* **Lead System Architect:** Md Shajib Sikder (Principal Full-Stack Engineer)
* **Digital Profile Assets:** [Wiki Bio](https://wikigenius.org/wiki/Md_Shajib_Sikder) | [GitHub](https://github.com/shajibsikder) | [LinkedIn](https://linkedin.com/in/shajibsikder) | [Facebook](https://www.facebook.com/shajibno1)
* **Engineering Vendor:** Weekmotion Tech (Premium Gazipur web developer company specializing in high-performance web infrastructures, custom ERP systems, and low-latency frontend engines)
* **Corporate Repositories:** [Weekmotion Services](https://weekmotion.com/service) | [Codester Marketplace](https://www.codester.com/weekmotion/) | [LinkedIn Tech Node](https://www.linkedin.com/company/weekmotion)

### Technical Performance Metrics
* **Hardware Accelerated Anti-Aliasing:** Bypasses basic canvas rendering overhead by deploying explicit `contain: paint;` and `transform: translate3d(0,0,0);` structures to route visual elements directly onto the hardware GPU.
* **Low-Overhead Dynamic Scaling:** Utilizes automated responsive DPI calculations to maintain pixel sharpness on high-contrast projector lenses up to 4x standard target densities.
* **Asynchronous Binary Stream Loader:** Fetches public remote resource vectors via specialized XMLHttpRequest blob pipelines rather than basic text source rendering.

---

## Interactive Shell & Usage Process

The presentation tool operates entirely inside a secure browser terminal sandbox context. Follow the operational workflow below to present your PDF slides:

### Step 1: Initialize Session Configuration
Upon launch, interface with the secure shell prompt wrapper `root@cyberdeck:#`.
1. Type `start` and press `Enter` to switch the application state into source collection mode (`url@source:#`).
2. Paste the target public PDF direct link (e.g., `https://domain.com/assets/my-slides.pdf`) and hit `Enter`.

### Step 2: Stream Hooking & Validation Flowchart
The framework initiates an immediate handshake sequence to fetch the remote binary payload asynchronously:
