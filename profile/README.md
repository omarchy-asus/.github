# omarchy-asus

**ASUS laptops that just work on Omarchy.**

Every ASUS laptop has a short list of things that don't quite work on Linux. Each one can be
fixed, so we fix them, test them on real hardware, and send every fix upstream to
[Omarchy](https://github.com/basecamp/omarchy), the kernel, NVIDIA and Hyprland. The goal is
to make ourselves unnecessary.

### Repos

- **[omarchy-asus](https://github.com/omarchy-asus/omarchy-asus)**: the hub. A signed pacman
  repo of patched builds, the recipes and tooling behind it, and the issue tracker for all of
  it.
- **omarchy** (coming soon): a fork of basecamp/omarchy where ASUS fixes are written in
  Omarchy's own shape and sent upstream as pull requests.
- **omarchy-pkgs** (coming soon): a fork of omacom/omarchy-pkgs for upstream package pull
  requests.

### Status

Experimental. Built today for the ROG Zephyrus G16 GA605. More models as people bring them.

### Get involved

Have an ASUS laptop? [Open an issue](https://github.com/omarchy-asus/omarchy-asus/issues)
with your model and what's broken. Fixes, testing and ideas are all welcome. Start with
[CONTRIBUTING](https://github.com/omarchy-asus/omarchy-asus/blob/main/CONTRIBUTING.md).

**Rule 1:** Help make the software better.

**Rule 2:** Don't be a dick.

<sub>An unofficial community project, not affiliated with Basecamp, Omacom or ASUS. Maintained by [@rdoupe](https://github.com/rdoupe).</sub>
