Here are the step-by-step instructions for both ways:

### Way 1: Push the Entire Folder to the Repository

#### 1. **Navigate to Your Repository**
   ```sh
   cd /path/to/your/local/repository
   ```

#### 2. **Initialize Git (if not already initialized)**
   ```sh
   git init
   ```

#### 3. **Add All Files to Staging Area**
   ```sh
   git add .
   ```

#### 4. **Commit the Changes**
   ```sh
   git commit -m "Initial commit with all files"
   ```

#### 5. **Add Remote Repository**
   (If you haven't set the remote yet, you need to add it)
   ```sh
   git remote add origin https://github.com/yourusername/your-repo.git
   ```

#### 6. **Push the Changes to GitHub**
   ```sh
   git push -u origin main
   ```

### Way 2: Push Only One Specific File to the Repository

#### 1. **Navigate to Your Repository**
   ```sh
   cd /path/to/your/local/repository
   ```

#### 2. **Initialize Git (if not already initialized)**
   ```sh
   git init
   ```

#### 3. **Add the Specific File to Staging Area**
   ```sh
   git add path/to/your/file
   ```

#### 4. **Commit the Changes**
   ```sh
   git commit -m "Add specific file"
   ```

#### 5. **Add Remote Repository**
   (If you haven't set the remote yet, you need to add it)
   ```sh
   git remote add origin https://github.com/yourusername/your-repo.git
   ```

#### 6. **Push the Changes to GitHub**
   ```sh
   git push -u origin main
   ```

### Detailed Example

#### Example for Pushing the Entire Folder

1. **Navigate to your local repository:**
   ```sh
   cd /path/to/your/local/repository
   ```

2. **Initialize Git:**
   ```sh
   git init
   ```

3. **Add all files to the staging area:**
   ```sh
   git add .
   ```

4. **Commit the changes:**
   ```sh
   git commit -m "Initial commit with all files"
   ```

5. **Add the remote repository:**
   ```sh
   git remote add origin https://github.com/yourusername/your-repo.git
   ```

6. **Push the changes to GitHub:**
   ```sh
   git push -u origin main
   ```

#### Example for Pushing Only One Specific File

1. **Navigate to your local repository:**
   ```sh
   cd /path/to/your/local/repository
   ```

2. **Initialize Git:**
   ```sh
   git init
   ```

3. **Add the specific file to the staging area:**
   ```sh
   git add path/to/your/file
   ```

4. **Commit the changes:**
   ```sh
   git commit -m "Add specific file"
   ```

5. **Add the remote repository:**
   ```sh
   git remote add origin https://github.com/yourusername/your-repo.git
   ```

6. **Push the changes to GitHub:**
   ```sh
   git push -u origin main
   ```