# $arraySlice
slices an array from x to y from `$textsplit`

#### Usage: `$arraySlice[from;to]`
<br/>
<discord-messages>
	<discord-message :bot="false" role-color="#ffcc9a" author="Member">
		!!exec $textsplit[Mika Wiki Mido Rake; ] {{ '\n' }} $arraySlice[2;3] {{ '\n' }} $arrayJoin[ ]
	</discord-message>
	<discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
		Wiki Mido
	</discord-message>
</discord-messages>

##### Function Difficultly: <Badge type="tip" text="Easy" vertical="middle" /> 
###### Tags: <Badge type="tip" text="array" vertical="middle" /> <Badge type="tip" text="slice" vertical="middle" /> <Badge type="tip" text="textsplit" vertical="middle" /> <Badge type="tip" text="keep" vertical="middle" />