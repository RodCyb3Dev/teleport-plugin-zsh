# teleport-plugin-zsh

To add Teleport's command-line tool (`tsh`) to your `.zshrc` or include it as an Oh My Zsh plugin, you need to follow these steps:

### Adding Teleport to Oh My Zsh Plugins

If you prefer to add Teleport as a plugin in Oh My Zsh, you can create a custom plugin for it:

1. **Create a new directory for the custom plugin**:
   ```sh
   mkdir -p ~/.oh-my-zsh/custom/plugins/teleport
   ```

2. **Create a plugin script**:
   ```sh
   nano ~/.oh-my-zsh/custom/plugins/teleport/teleport.plugin.zsh
   ```

3. **Add the following content to the `teleport.plugin.zsh` file**:
   ```sh
    
   ```

4. **Save and close the file** (in nano, you can do this by pressing `CTRL + X`, then `Y`, and `Enter`).

5. **Edit your `.zshrc` file to include the new plugin**:
   ```sh
   nano ~/.zshrc
   ```

6. **Add `teleport` to the list of plugins**:
   ```sh
   plugins=(git teleport)
   ```

7. **Save and close the file** (in nano, you can do this by pressing `CTRL + X`, then `Y`, and `Enter`).

8. **Reload your shell configuration**:
   ```sh
   source ~/.zshrc
   ```

9. **To check run**:
   ```sh
   tsh
   ```
By following these steps, you will have added Teleport's `tsh` command to your Zsh configuration, enabling command completion and making it easier to use Teleport from your terminal.

Citations:
