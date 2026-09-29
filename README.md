# GoToMyPC Connection Tester

Single-page web app (`index.html`) that checks whether a network can reach the domains GoToMyPC needs,
based on https://support.gotomypc.com/help/what-are-the-optimal-firewall-configurations.

Host it on any static HTTPS host (e.g. GitHub Pages) and send the link to an end user. The checks run automatically on load.
Edit the `ENDPOINTS` array in `index.html` to change what is tested.
