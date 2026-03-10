# MoviesWPF

MoviesWPF is a desktop movie browser UI I built to practice WPF and MVVM in a hands-on way. It started as a design-first learning project, then I cleaned it up in March 2026 so the code and docs are easier to follow. It is still a work in progress, but the core structure is in place.

## Tech Stack
- C#
- WPF (.NET Framework 4.7.2)
- MVVM pattern
- XAML resource dictionaries (styling/theming)

## Getting Started
1. Clone this repository.
2. Open `MoviesWPF.sln` in Visual Studio (2019 or newer).
3. Build and run the `MoviesWPF` project.

Notes:
- This is a classic .NET Framework WPF app (not SDK-style).
- If build tools are missing, install the .NET desktop development workload in Visual Studio.

## What I Built & Why
I wanted to get better at structuring a desktop UI with MVVM instead of putting everything in code-behind. So I built a small movie-focused interface with custom styles, basic view model wiring, and a reusable theme setup. The goal was to learn the architecture and UI flow first, then iterate on real data features after that foundation was stable.

## What I Learned
- How to split WPF UI code into views, view models, and shared base classes.
- How resource dictionaries can keep styles consistent across the app.
- How easy it is to break bindings in XAML, and how important naming + DataContext wiring is.
- Why early UI prototypes are useful, even before the full backend/data layer is finished.

## Planned Improvements
- [ ] Wire the left menu buttons to actual view navigation.
- [ ] Replace placeholder movie content with real movie records.
- [ ] Add search/filter logic behind the search box.
- [ ] Improve accessibility and keyboard navigation.

## Project Timeline
- **Started:** May 2023 (initial project structure and homepage UI commits)
- **Refreshed:** March 2026 (cleanup pass, bug fixes, documentation polish)
