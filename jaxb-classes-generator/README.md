Generate JAXB classes from XML files received from server...

1. Generate XSD from XML: `trang ~/Dokumenty/getRozvrhByMistnost.xml getRozvrhByMistnost.xsd`
1. `mkdir src`
1. `xjc -d src -p cz.honzakasik.upol.where2study.restclients.jaxbmodels.mistnostiinforesponse getMistnostiInfo.xsd`
