# io7 IoT Lamp with Switch and Dashboard

Adds a Node-RED Dashboard 2.0 UI to the lamp + switch flow. A ui-switch widget sends `on`/`off` commands to `lamp1`, while the lamp's own status events drive the widget's displayed state, so the dashboard always reflects the real device — whichever path changed it.

Import `flows.json`, install `@flowfuse/node-red-dashboard`, keep the switch widget's "pass through" option off (it would otherwise loop), and open `http://<your-host>:1880/dashboard`. Run the dummies with `npx github:io7lab/io7dummy-device lamp` and `... button`.

See Chapter 3, Section 3.4.3 of the book.

<img width="1624" height="963" alt="Screenshot 2025-09-24 at 10 57 30 PM" src="https://github.com/user-attachments/assets/8224c7e4-931b-49c8-ae6b-9f5d6c06d595" />
