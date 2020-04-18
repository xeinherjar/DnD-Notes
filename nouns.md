# Nouns: People, Places and things

Types
  - item
  - lore
  - npc
  - place

Syntax:\
Type Identifier {
  shortDescription: String,
  stats: Optional[Stats[LVL AC STR DEX CON INT WIS CHA]],
  notes: List[String],
}

npc Toblen Stonehill {
    Innkeeper of Stonehill in Phandalin

    - Human
}

npc Elmar Barthen {
  Owns a trading post; owes money to the party if you are using the
  "Meet Me in Phandalin" adventure hook
}

npc Daran Edermath {
    Member of the Order of the Gauntlet with a quest for the party
}

npc Linene Graywind {
    Runs a trading post and offers a reward for retrieving her supplies
}

npc Halia Thornton {
    Member of the Zhentarim with a quest for the party
}

npc Qelline Alderleaf {
    Helpful halfling farmer whose son, Carp, knows a secret way into the
    Redbrands' hideout
}

npc Sister Garaele {
    Elf cleric of Tymora and Harper agent with a quest for the party
}

npc Harbin Wester {
    Townmaster of Phandalin with a quest for the party
}

npc Sildar Hallwinter {
    Member of the Lords' Alliance with two quests for the party
}
