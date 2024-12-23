# Intro To Golang

## Description

Never tried Go yet? Or you did but just need a refresher? In this campaign, we will take you on a guided journey into the world of Go. 

We start with understanding what Go is, installing it on your computer, and running your first Go program. Then, we explore Go's current role in the tech industry, focusing on its dominance in container technologies and comparing it with other popular programming languages like Python and Rust.

Lastly, we delve into Go's syntax and semantics, covering functions, types, control flow (e.g., `switch-case`), and module management. You will also learn to build Go programs in an offline environment.


---

## Learning Outcomes

By the end of this campaign, you will be able to:
- Explain what Go is.
- Use Go's CLI tool to build, format, and install Go code and programs.
- Write basic Go syntax.
- Write simple programs in Go.

## Quests

### Quest 1 - Go Begin Your Go Journey
### Quest 2 - Go Where Go Is
### Quest 3 - Go Build Your Go Fundamentals

---

## Detailed Learning Outcomes

After completing all quests, you will:
- Understand Go's syntax and semantics, including types, functions, module imports, and project structure.
- Explain how to use Go's subcommands.
- Add and use third-party Go modules in your project.
- Build projects for offline environments using Go's vendoring feature.

---

## Quest Details

### **Introduction**

Now that you are familiar with Go or Golang, let's start building your Go fundamentals. We will explore:
- Go's syntax.
- Functions and control structures.
- Adding third-party dependencies (Go modules).
- Vendoring Go modules for offline builds.


---

### **Step 1: Getting Familiar with Go's Subcommands**

Go provides several built-in commands for managing projects. To see a list of available commands, run:

```bash
go help
```

**Usage:**

```
go <command> [arguments]
```

**Common Commands:**
- `go run`: Compiles and runs Go programs.
- `go build`: Builds an executable binary.
- `go doc`: Displays documentation for packages and symbols.
- `go fmt`: Formats Go source code.
- `go install`: Installs Go utilities as a package manager.

#### Examples:

1. **Running a Program:**
   ```bash
   go run main.go
   ```

2. **Building an Executable:**
   ```bash
   go build
   ./intro-to-golang  # For Linux/Mac
   intro-to-golang.exe  # For Windows
   ```

3. **Viewing Documentation:**
   ```bash
   go doc fmt.Println
   ```

4. **Installing a Go Utility:**
   ```bash
   go install github.com/charmbracelet/glow@latest
   ```

**Tip:** If you're ever unsure, run `go help` for guidance.

---

### **Step 2: Variables**

There are three main ways to declare variables in Go:

1. **Using `var` keyword:**
   ```go
   var x int = 10
   ```

2. **Using `const` keyword (for constants):**
   ```go
   const Pi = 3.14
   ```

3. **Using short assignment (`:=`):**
   ```go
   y := 20
   ```

**Note:** Constants are immutable, but their values can be assigned to mutable variables.

---

@StackUp
## Recap

Go's CLI offers a variety of tools for building and managing projects. With practice, you will become familiar with commands like `go run`, `go build`, `go doc`, and more. Remember, you can always run `go help` to get additional information on commands.

Next, we will dive deeper into Go's syntax. Go's simplicity ensures that you'll quickly grasp the basics and be ready to build more complex applications.
