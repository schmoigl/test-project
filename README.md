
# Quarto Template Repo

This is a template repo for the field course "Data Science and Machine Learning".

**Live site:** <https://schmoigl.github.io/test-project/> (rebuilt automatically from `index.qmd` on every push to `main`)

## The Teams

Add your team (name + members) on an empty `- ` line below:

- No Overfitting, Just Overthinking: Greta Simeliunaite and Csenge Soter
- R.-Bytes-Loss(): Deim, Tartarotti, Weber
- commit(ment) issues: Tim Brecht, Panna Bodnar, Chiara D'Amico
- Git Happens: Sophia Leah Ravner, Alesia Kokonaj, Jennifer Emilio
- The Biased Priors: Ryan McCann, Lorenz Rausch, Lorenz Bodner
- The Matrix Confusers : Thomas, Isabella 
- Maximum Likelihood of passing: Peter Sparks, Paul Boissot, Anita Mor
- Code & Cognition: Emma Boydens, Jens Vorsselmans, Marie Pittevils

Don't forget to pick a funny name that is a pun on the contents of this class! Some inspirations from the past:

- VS Code Pets Owners Association
- Lost in the Random Forest
- 404: Team Name Not Found
- YAML(E) — Yet Another Machine Learning Expert
- People of the Python Cult
- The Almighty Repo Forkers
- The Viz Wizards


## Adding your team via a pull request

**You'll need:** a GitHub account and [Git](https://git-scm.com/downloads) installed.

You can't push to this repo directly, so you work on your own copy (a *fork*) and then ask for your change to be merged (a *pull request*).

1. **Fork the repo:** on <https://github.com/schmoigl/test-project>, click **Fork** (top right). This creates `https://github.com/<your-username>/test-project`.

2. **Clone your fork:**
   ```bash
   git clone https://github.com/<your-username>/test-project.git
   cd test-project
   ```

3. **Create a branch:**
   ```bash
   git checkout -b add-team-yourteamname
   ```

4. **Edit `README.md`:** under "The Teams", write your team on an empty `- ` line and save the file.

5. **Commit and push to your fork:**
   ```bash
   git add README.md
   git commit -m "Add team <name>"
   git push -u origin add-team-yourteamname
   ```

6. **Open the pull request:** on your fork on GitHub, click **Compare & pull request**. Check that the base repository is `schmoigl/test-project` with base `main`, then click **Create pull request**.

### Merge conflict?

Another team probably edited the same line. Get the latest version of the original repo and merge it into your branch:

```bash
git pull https://github.com/schmoigl/test-project.git main
```

Open `README.md`, keep both teams, and delete all `<<<<<<<`, `=======` and `>>>>>>>` lines. Then:

```bash
git add README.md
git commit -m "Resolve merge conflict"
git push
```

The pull request updates automatically.
