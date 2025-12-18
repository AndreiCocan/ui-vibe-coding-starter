Your task is to implement a new route on /dashboard, following the design + development brief below. Implement thoroughly, in a step-by-step manner, and use built-in, standard Tailwind CSS design tokens instead of hardcoding values.

For colors and font families, use the defined values present in
@tailwind.config.js, e.g. 'bg-primary-500' etc. instead of the hardcoded primary/secondary values in the JSON brief. For one-off colors/grays etc. the JSON values are acceptable.

**Requirements**

- responsive (full width bg with centered content on larger screens)
- theme aware components with light and dark mode support (you can toggle with @ThemeSwitch.tsx; make sure to include that in the menu bar)
  - update @data/config/colors.js to match the colors in the design brief
  - *important* make sure to include light and dark mode colors by using Tailwind's dark mode classes (dark:)
  - all components must adapt to theme changes
- *do not use* magic strings, hex values, or px values. Replace all with Tailwind classes if possible.
- split reusable or complex parts of the UI into components so the code is maintainable and easy to understand.
- if any sample data is generated, place it in a separate file to keep the code clean.

**Note**

- the app is already running a dev server at port 6006

**Assignment brief**

<paste design brief from Step 1 here>

**Design specification**

<paste JSONC design specification from Step 1 here>
