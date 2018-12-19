# postcss-simulate-element-state
A postcss plugin used in front-end build useful for simulating dom element states. The plugin finds css rules like :focus, :active, :hover and inserts similar rules with [data-simulate-{state}] selectors. The plugin is only used in storybook/styleguide front-end build pipeline, the production bundles do not contain the selectors for simulating dom element states.
