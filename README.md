# Gateway from Modbus to Ethernet IP with Optix
This project shows how to convert tags coming from a Modbus driver to an RA Ethernet IP. Tags are synchronized even if not used in UI.
## Instructions
- Open project
- Define input tags in the `Modbus station`
- Create Dynamic Links from `Mosbus` tags to `Ethernet IP` tags (and not viceversa)
- Browse to `NetLogic/VariableSynchronizer` and populate the `TagsToSync` variable to the container of the tags to be synchronized
- Launch the application