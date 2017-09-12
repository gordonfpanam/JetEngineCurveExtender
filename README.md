# Jet Engine Curve Extender for Kerbal Space Program
Galileo's Planet Pack has at least one world, Tellumo, with a very thick oxygen atmosphere. The pressures inhibit rocket engines, but in theory jet engines could thrive there.

These patches extend the stock atmCurve values for Kerbal Space Program's jet engines. On Kerbin or Laythe in the stock game, the patches don't have any impact. In a thick, oxygen-rich world like Tellumo in Galileo's Planet Pack, they'll generate more thrust in thicker air at the expense of greater fuel consumption.

The repository contains a Module Manager patch for each engine, and a Microsoft Excel spreadsheet with raw thrust data. The spreadsheet has graphs to help match the measured thrust curves against the stock game's atmCurve float curves.

I sampled the thrust data using the Advanced Jet Engines add-on, and changing the home world to Tellumo similar to GregroxMun's Alien Space Programs. Advanced Jet Engines simulates jet behaviour using code from NASA's EngineSim tool.

To use the Module Manager patches, install a current edtion of Module Manager into your KSP installation's GameData folder, then copy the JetEngineCurveExtender folder from here to your GameData folder as well.
