# Profile README upgrade

Files:
- `README.md` — new Aurora / 3D profile design
- `.github/workflows/profile-3d.yml` — generates the 3D contribution image
- `.github/workflows/generate-snake.yml` — generates the contribution snake

After adding these files to the profile repository:
1. Open **Actions**.
2. Run **GitHub-Profile-3D-Contrib** manually once.
3. Run **Generate Contribution Snake** manually once.
4. Wait for both workflows to finish.
5. Open the profile README.

The README intentionally avoids the broken public GitHub stats/activity endpoints that appeared in the previous version. It keeps the working streak/profile-summary cards and adds a generated 3D contribution visualization.
