# Git Repository: spm-exp2

This repository is created for testing and demonstrating pull and push operations in a Git environment.

## How to Perform Pull Operation

1. Open a terminal or command prompt.

2. Navigate to the local repository directory using the `cd` command:

    ```bash
    cd path/to/spm-exp2
    ```

3. Ensure you are on the branch where you want to pull changes:

    ```bash
    git checkout your-branch
    ```

4. Pull the latest changes from the remote repository:

    ```bash
    git pull origin your-branch
    ```

   Replace `your-branch` with the name of the branch you are working on.

## How to Perform Push Operation

1. Open a terminal or command prompt.

2. Navigate to the local repository directory using the `cd` command:

    ```bash
    cd path/to/spm-exp2
    ```

3. Stage your changes using the following command (replace `your-file` with the actual file or use `.` to stage all changes):

    ```bash
    git add your-file
    ```

4. Commit your changes:

    ```bash
    git commit -m "Your commit message here"
    ```

5. Push your changes to the remote repository:

    ```bash
    git push origin your-branch
    ```

   Replace `your-branch` with the name of the branch you are working on.

## Important Notes

- Ensure you have the necessary permissions to pull and push to the Git repository.
- If using a private repository, set up SSH keys or provide a personal access token for authentication.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
