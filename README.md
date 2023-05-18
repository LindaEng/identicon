# Identicon Generator

This is an Elixir project that allows you to generate unique identicons for GitHub profiles. Identicons are simple, visually appealing icons generated based on a string of text.

## Installation

To install and run this project on your local machine, please follow these steps:

### Prerequisites

- Elixir and Erlang installed on your system. You can download them from the official Elixir website: [https://elixir-lang.org/install.html](https://elixir-lang.org/install.html)

### Clone the Repository

1. Open your terminal.
2. Change to the directory where you want to clone the project.
3. Run the following command to clone the repository:

git clone https://github.com/your-username/identicon.git


   Replace `your-username` with your GitHub username.

### Build Dependencies

1. Change to the project's root directory:

cd identicon


2. Fetch and compile the project dependencies by running:

mix deps.get


### Generate Identicons

To generate an identicon, you can make use of the provided `Identicon` module.

1. Start an interactive Elixir shell (IEx) by running:

iex -S mix


2. Inside the IEx shell, you can generate an identicon by calling the `Identicon.generate/1` function and passing a string as the argument. For example:

```elixir
iex> Identicon.generate("JohnDoe")
```


This will generate an identicon based on the provided string.

The generated identicon will be saved as a PNG image file in the project's root directory.