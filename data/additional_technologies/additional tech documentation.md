The CSV file in this directory allows a user to add their own technology costs and
heat rate assumptions to cases.

technology: Name of the technology. Should be distinct in some way from the ATB names,
especially the ATB <technology>_<tech_detail> combination.

basis_year: The year that technology costs and attributes are based on.

capex: USD/MW capital expenses, including construction financing costs, etc. Be sure to
convert from $/kW.

capex_mwh: USD/MWh capital expenses, including construction financing costs, etc. Used
for storage resources such as batteries.

o_m_fixed_mw: Fixed O&M costs per MW-year.

o_m_fixed_mwh: Fixed O&M costs per MWh-year. Used for storage resources such as batteries.

o_m_variable_mwh: Variable O&M costs per MWh.

waccnomtech: Nominal weighted average cost of capital.

dollar_year: Year that dollars are calculated for. This is used to convert costs to a
consistent dollar year across inputs.

heat_rate: MMBTU per MWh

notes: Not used in calculations, this is a place to document sources, etc.
