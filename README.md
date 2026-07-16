# Angular Admin Template

A collection of admin dashboard template archives for Angular, packaged for reuse across projects. There is no source checked into the repo directly - the code lives inside four RAR archives:

- `Angular-v6-skeleton.rar` - bare admin layout/skeleton for Angular 6
- `Angular-v6-demo.rar` - fully wired demo build on the Angular 6 skeleton
- `Angular-v8-skeleton.rar` - bare admin layout/skeleton for Angular 8
- `Angular-v8-demo.rar` - fully wired demo build on the Angular 8 skeleton

## Using it

Extract whichever variant you need (requires `unrar` or an archive tool that supports RAR):

```bash
git clone https://github.com/er-shrey/angular-admin-template.git
cd angular-admin-template
unrar x Angular-v8-skeleton.rar
```

The original README had an incomplete "Pass:" line, suggesting the archives may be password-protected - if `unrar` prompts for a password and you don't have it, check with the repo owner.

Once extracted, treat it as a standard Angular CLI project: `npm install`, then `ng serve` (Angular 6) or the equivalent Angular 8 CLI commands, from inside the extracted folder - check for its own `package.json`/`angular.json` for exact scripts.
