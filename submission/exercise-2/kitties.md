-Calls
	1)create
-Storages
	1)Kitties: double_map AccountId, u32 => Option<Kitty>
	2)NextKittyId: u32
-Types
	1)struct Kitty([u8; 16])
-Events
	1)KittyCreated
		a)owner: AccountId
		b)kitty_id: u32
		c)kitty: Kitty
