# Private deployment

1. Create a **private** GitHub repository named `jojo-birthday-story`.
2. Upload the contents of this folder, not the ZIP.
3. In Cloudflare Pages, connect only that private repository.
4. Framework preset: None. Build command: leave blank. Output directory: `/`. Production branch: `main`.
5. Do not share the temporary address yet.
6. In Cloudflare Zero Trust, add One-time PIN as the identity provider.
7. Add a Self-hosted Access application using the exact Pages hostname.
8. Create an Allow policy with the exact two approved email addresses. Add the addresses in Cloudflare only, never in the website or GitHub.
9. Set session duration to 24 hours.
10. Test one approved and one unapproved address in separate Incognito windows.
11. Only then share the protected URL.

The repository must remain private. The website includes no analytics. Original image metadata has been removed from the packaged copies.
