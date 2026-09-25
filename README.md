# Subnetly

Subnetly is a lightweight, browser-based IPv4 subnet calculator and learning tool. It helps you:

- calculate subnet ranges from a CIDR block
- compare equal-subnet (FSLM) and variable-length subnet mask (VLSM) planning
- visualize binary and mask boundaries
- review private IP class examples
- practice subnetting with a built-in quiz

The app runs entirely on the client side, so there is no backend or data sent anywhere when you use it.

## Features

- CIDR network input and validation
- FSLM subnet splitting with host counts and summary cards
- VLSM allocation based on required hosts per subnet
- Address tables with network, broadcast, usable range, wildcard, and binary details
- Binary visualizer for prefix-length and mask interpretation
- Private network examples for 10.0.0.0/8, 172.16.0.0/12, and 192.168.0.0/16
- Practice quiz for subnetting fundamentals
- Light/dark theme toggle

## Project structure

```text
subnetly/
├── README.md
├── Subnetly/
│   ├── index.html
│   └── icon.svg
└── .gitignore
```

## Run locally

Since this project is a static HTML app, you can open it directly in a browser:

1. Clone the repository.
2. Open `Subnetly/index.html` in your browser.

Optional local web server:

```bash
cd subnetly
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/Subnetly/
```

## Notes

- The app is designed for IPv4 subnetting exercises.
- It is intended for learning and quick planning, not for production network automation.
- No external service is required for the calculator to function.

## License

This project does not currently declare a license. If you plan to share or publish it, consider adding an appropriate open-source license such as MIT.
