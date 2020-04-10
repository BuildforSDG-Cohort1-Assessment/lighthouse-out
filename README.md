# lighthouse-out
This action sends the lighthouse assertion summary to our backend API

## Inputs

### `lang`

**Required** The primary language with which the developer coded the solution being tested . Default is `"javascript"`.

### `server`

**Required** The base backend API endpoint to send the report data to . Default is `"https://us-central1-buildforsdg.cloudfunctions.net"`.

## Example Usage

```bash
- name: Report Lighthouse
  uses: BuildforSDG-Cohort1-Assessment/lighthouse-out@v1
```

