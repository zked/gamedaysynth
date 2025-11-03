# gamedaysynth

Asos wants to include their own user journey as a signal to Pathpoint’s checkout stage.  User journey will be simulated with New Relic Synthetics . 

The synthetics script steps will be the following:
- Navigate to “https://www.asos.com/”
- Accept cookies (Clear cache before running Selenium IDE on Firefox)
- Choose “MEN”
- Select a product, choose size and add to bag

PS1: Use firefox and selenium IDE extension to record the journey.
PS2: Use New Relic SideKick to convert .side file into New Relic compatible format. (https://github.com/newrelic-experimental/newrelic-sidekick)
PS3: Use AI assistant of your choice to overcome issues.
