<p>
    <picture>
        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kikotxyz/.github/main/content/kikot.svg">
        <img alt="kikot" src="https://raw.githubusercontent.com/kikotxyz/.github/main/content/kikot.svg" width="auto" height="60">
    </picture>
</p>

The kikot platforms.

---

Currently, we manage the following:

- The **kikot MRK4** (legacy code base with a single repository per service)
- The **kikot MRK5** (single mono repo [`kikot`](https://github.com/kikotxyz/kikot))
- The **babykkt MRK1** (single mono repo [`babykkt`](https://github.com/kikotxyz/babykkt))
- The **daam.fund** public website repo ([`daam.fund`](https://github.com/kikotxyz/daam.fund))

All the platform repositories (kikot MRK4, MRK5, babykkt) use a shared code base (like APIs, composables, etc.). For the legacy code (MRK4), the shared code base is located in the [`lib repo`](https://github.com/kikotxyz/lib). Since the introduction of the mono repositories (MRK5+), we have introduced the [`pkg repository`](https://github.com/kikotxyz/pkg) not to mix legacy code with the new one.

> Note: The pkg repository starts as **v5** to follow the semantic versioning.

## Main branch protection

All repositories have protected the main branch. So, please, for any development, use issues and their respective branches, plus pull requests.
