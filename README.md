# valorant-agent-names
Current Version: 4.04

```C
std::string GetCharacterName(int id)
{
	switch (id)
	{
	case 13040168: return XorStr("ASTRA").c_str();
		break;
	case 13047856: return XorStr("JETT").c_str();
		break;
	case 13029446: return XorStr("CHAMBER").c_str();
		break;
	case 13036743: return XorStr("KILLJOY").c_str();
		break;
	case 13027404: return XorStr("RAZE").c_str();
		break;
	case 13046206: return XorStr("REYNA").c_str();
		break;
	case 13045339: return XorStr("SAGE").c_str();
		break;
	case 13033116: return XorStr("SKYE").c_str();
		break;
	case 13042446: return XorStr("NEON").c_str();
		break;
	case 13038058: return XorStr("VIPER").c_str();
		break;
	case 13026811: return XorStr("BREACH").c_str();
		break;
	case 13041531: return XorStr("BRIMSTONE").c_str();
		break;
	case 13034325: return XorStr("CYPHER").c_str();
		break;
	case 13046997: return XorStr("OMEN").c_str();
		break;
	case 13039171: return XorStr("PHOENIX").c_str();
		break;
	case 13035537: return XorStr("SOVA").c_str();
		break;
	case 13044267: return XorStr("YORU").c_str();
		break;
	case 13032022: return XorStr("KAY/O").c_str();
		break;
	case 13046159: return XorStr("BOT").c_str();
		break;
	case 13046565: return XorStr("MED BOT").c_str();
		break;
	case 13046553: return XorStr("HARD BOT").c_str();
		break;
	case 13041521: return XorStr("Astral Form").c_str();
		break;
	default:
		return std::to_string(id);
		break;
	}
}
```
