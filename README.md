git# Group-C-Final-Project

## Contributing Guidelines

### Branch Naming and Workflow

- Each developer should create a branch for their assigned section. Use descriptive branch names like `header`, `footer`, `about-page`, etc.
- Only make changes to the section you are assigned to. Do not modify other sections.

### Assigned Sections

- **Header Section**: 
  - Responsible for the header part of `index.html` and relevant styles in `./styles/header.css`.
  
- **Footer Section**: 
  - Responsible for the footer part of `index.html` and relevant styles in `./styles/footer.css`.

- **About Page**: 
  - Responsible for the hero page section of `index.html` and relevant styles in `./styles/hero.css`.

### Workflow

1. Fork and Clone the repository:
   ```sh
   git clone git@github.com:your-username/Group-C-Final-Project.git
   cd Group-C-Final-Project

2. Create a branch for your section
    ```sh
    git checkout -b header  # Replace 'header' with your section name

3. Make changes to your assigned section only.
    You can name your css file after your section name.For example `header.css`. 

4. Commit your changes:
    ```sh
    git add .
    git commit -m "Describe your changes here"

5. Push your branch:
    ```sh
    git push origin header  # Replace 'header' with your section name

6. Create a Pull Request:
    On GitHub, create a pull request from header to main.