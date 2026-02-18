---
campanha: O Esquecimento
status: em andamento
---
---
# 🐉 Painel da Campanha: O Esquecimento

## 📜 Próxima Sessão & Tarefas
```tasks
not done
path includes O Esquecimento
````

---

## 🎲 Crônicas das Sessões


```dataview
TABLE data as "Data"
FROM "segundo cérebro/30 projetos/03 RPG e Worldbuilding/O Esquecimento/10 Diário de Sessão"
WHERE tipo = "sessão de rpg"
SORT numero_sessao DESC
LIMIT 10
```

---

## 🌍 O Mundo e Seus Habitantes

### 🏙️ Lugares Descobertos
```dataview
LIST 
WHERE tipo = "local rpg"
```

### 👤 NPCs e Aliados

```dataview
TABLE raça as "Raça", classe as "Classe", relacao as "Status"
FROM "segundo cérebro/30 projetos/03 RPG e Worldbuilding/O Esquecimento"
WHERE tipo = "npc"
SORT file.name ASC
```

---

## 📖 Grimório de Annaeru

```dataview
TABLE nivel as "Nível", escola as "Escola"
WHERE tipo = "magia rpg"
SORT nivel ASC, file.name ASC
```

---

## 🎒 Tesouros e Itens Mágicos

```dataview
TABLE tipo_item as "Tipo", portador as "Com quem está"
WHERE tipo = "loot rpg"
```
