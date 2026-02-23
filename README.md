# Ruby Quest
## From Zero to Gem. A Foundational Overview for a Python Developer

A beginner Ruby project that prints `Hello, World!` to the terminal. This is the first step in a structured Ruby learning journey, transitioning from Python to Ruby.

---

##  About This Project

This repository contains a single Ruby script that outputs a greeting to the console. It serves as the foundation for learning Ruby syntax, setting up a Ruby development environment on Linux/Ubuntu, and establishing a GitHub workflow.

---

##  System Requirements

| Requirement | Details |
|---|---|
| Operating System | Ubuntu 18.04 or higher |
| Ruby Version | 3.2.2 (managed via rbenv) |
| Editor | VS Code (with Ruby LSP extension) |
| Version Manager | rbenv |
| Package Manager | RubyGems (gem) + Bundler |

---

##  Installation & Setup

### Step 1 — Install System Dependencies

Open your Ubuntu terminal and run:

```bash
sudo apt update && sudo apt upgrade -y
```

```bash
sudo apt-get install -y git curl libssl-dev libreadline-dev zlib1g-dev \
autoconf bison build-essential libyaml-dev libncurses5-dev libffi-dev libgdbm-dev
```

### Step 2 — Install rbenv (Ruby Version Manager)

```bash
curl -fsSL https://github.com/rbenv/rbenv-installer/raw/HEAD/bin/rbenv-installer | bash
```

Add rbenv to your shell:

```bash
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
source ~/.bashrc
```

Verify the installation:

```bash
rbenv -v
```

Expected output:
```
rbenv 1.2.0 (or similar)
```

### Step 3 — Install Ruby 3.2.2

```bash
rbenv install 3.2.2
rbenv global 3.2.2
```

Verify Ruby is installed:

```bash
ruby -v
```

Expected output:
```
ruby 3.2.2 (2023-03-30 revision e51014f9c0) [x86_64-linux]
```

### Step 4 — Install Bundler

```bash
gem install bundler
```

Verify:

```bash
bundler -v
```

### Step 5 — Clone This Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

##  How to Run the Program

Once you have Ruby installed and the repository cloned, running the program is a single command:

```bash
ruby hello.rb
```

**Expected output:**

```
Hello, World!
```

That's it! If you see `Hello, World!` printed in your terminal, your Ruby environment is set up correctly and everything is working.

---

##  Project Structure

```
ruby-hello-world/
└── hello.rb       # The Hello World Ruby script
└── README.md      # This file
```

---

##  What the Code Does

```ruby
puts "Hello, World!"
```

| Element | Explanation |
|---|---|
| `puts` | A built-in Ruby method that prints text to the terminal followed by a new line. Short for "put string." |
| `"Hello, World!"` | A string literal; the text to be printed. |

> **Python comparison:** `puts` in Ruby is the equivalent of `print()` in Python. The key difference is that `puts` always adds a newline at the end automatically.

---

##  VS Code Setup (Recommended)

For the best development experience, install these VS Code extensions:

- **Ruby LSP** by Shopify — provides autocomplete, inline error detection, and go-to-definition
- **VSCode rdbg Ruby Debugger** by KoichiSasada — adds debugging support

You can install them from the VS Code Extensions panel (`Ctrl + Shift + X`) by searching for each by name.

---

##  Learning Context

This project is **Phase 1, Step 8** of a structured Ruby learning journey for developers transitioning from Python. The broader learning path covers:

- **Phase 1:** Ruby Language Fundamentals
- **Phase 2:** Ruby Collections and Iteration
- **Phase 3:** Object-Oriented Ruby
- **Phase 4:** Ruby Ecosystem and Practical Tooling

I will keep updating my work here as I move to the remaining phases

---

##  Author

**Mercy Ndolo**  
Beginner Ruby developer | Transitioning from Python  
GitHub: [NdoloMwende](https://github.com/NdoloMwende)

---

##  License

This project is open source and available under the [MIT License](LICENSE).