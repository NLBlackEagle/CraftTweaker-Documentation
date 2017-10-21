# Part

A Part is the form an item is in, for example a gear or an ore.

## Importing the package
It might be required for you to import the package if you encounter any issues, so better be safe than sorry and add the import.  
`import mods.contenttweaker.Part;` 

## Retrieving such an object
You can either retrieve an existing Part using the [MaterialSystem](/Mods/Contenttweaker/Materials/MaterialSystem) or create an entirely new one using the [Part Builder](/Mods/ContentTweaker/Materials/Parts/Part_Builder)

<details>
	<summary>Following types are pre-registered (Headlines are the [Part Types](PartType)):</summary>
	<h4>Items:</h4>
		<ul>
			<li>Beam</li>
			<li>Bolt</li>
			<li>Casing</li>
			<li>Dense Plate</li>
			<li>Dust</li>
			<li>Gear</li>
			<li>Ingot</li>
			<li>Nugget</li>
			<li>Plate</li>
			<li>Rod</li>
		</ul>
	<h4>Blocks:</h4>
		<ul>
			<li>Block</li>
		</ul>
	<h4>Ores:</h4>
		<ul>
			<li>Ore</li>
			<li>Dense Ore</li>
			<li>Poor Ore</li>
		</ul>
	<h4>Fluids:</h4>
		<ul>
			<li>Molten</li>
		</ul>	
	<h4>Armor:</h4>
		<ul>
			<li>Armor</li>
		</ul>
</details>

## Fields
You can retrieve the following information from a Part:

| ZenMethod            | Return Type                            |
|----------------------|----------------------------------------|
| getName()            | String                                 |
| getUnlocalizedName() | String                                 |
| getPartType()        | [IPartType](IPartType)                 |
| getPartTypeName()    | String                                 |
| getOreDictPrefix()   | String                                 |
| getData()            | List<[IPartDataPiece](PartDataPiece)>  |