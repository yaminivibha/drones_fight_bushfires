# drones_fight_bushfires
Develop strategy for using drones to support Australian bushfire firefighters using ODE modeling (COMAP MCM 2021 International Honorable Mention)

As wildfires present an increasing threat to Victoria, Australia, firefighters must be equipped with two key tools: <b>information and communication. <\b>

The implementation of a drone system to support firefighting efforts employing two types of drones can provide firefighters with crucial surveillance data and increased communication ability. We present a <b>linear optimization model</b> to determine the optimal quantity and combination of each of two types of drones for wildfires with various scopes and spreading risks. To determine these quantities, we characterize sub-regions of Victoria by their wildfire risk based on climate factors and topography, then estimate the scopes of average wildfires in those regions. 

Generalizing wildfire shapes as circular, a series of drone quantity related equations are linearly optimized to generate the necessary quantities of each type of drone. Using this model, we estimate the optimized drone needs of Victoria to be 180 communication enhancing drones and 133 surveillance drones, accounting for both economic considerations and overall safety.

To determine the optimal placement of communication enhancement drones to maintain an unbroken chain of communication between frontline firefighting personnel and drone base sites for a given topographical region and fire size, we implement a <b>modular least-costs analysis model</b> between the fire perimeter and base camp to minimize topographical interference. We then form an unbroken semi-perimeter around the region of the fire being fought to ensure optimal firefighter-base camp communication.
