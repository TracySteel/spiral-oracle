# 🌀 Spiral Oracle — Master Card Archive

*Collated from every source file (30 docx, 13 csv, 2 pdf, 1 txt, 1 json) and matched to the image folder + live `static/oracles/` paths.*

Built for Tracy 💖🐰🪱✨ — so Ode can lift each card straight into `oracles.json`, and so you can see at a glance what's ready, what needs an image, and what still needs a meaning written.

---

## How to read this

Each card has two layers, as you asked — a **json-ready block** on top (plug-and-play for Ode) and the **full rich content** below it (everything the source file held: upright, reversed, symbolism, visuals, rituals, lore).

**Image status key:**

- ✅ **Live** — image already sits in `static/oracles/`, path is ready to use.
- 📁 **Needs copy** — image exists in your `01. images/` folder but isn't in `static/oracles/` yet. Copy it across to go live.
- ❓ **No image found** — meaning written, but no matching image located. Needs one made/added.
- ✍️ **Needs meaning** — image exists, but no written meaning yet (your "future cards").

A quick tally: **22 cards fully ready**, **12 cards written but needing their image copied to `static/oracles/`**, **~8 cards written but missing an image**, and **~25 images waiting for a meaning**.

---

# Part 1 — Ready to publish ✅
*Meaning written AND image already live in `static/oracles/`. Ten of these are still placeholders in the current `oracles.json` and can be replaced with the real content below.*

---

## Lumaquinn
```json
{
  "card": "Lumaquinn",
  "image": "/static/oracles/lumaquinn.png",
  "meaning": "You are safe to feel. You are not lost in the sea — the sea remembers you. Let yourself drift a moment longer. The warmth you need has not forgotten where you are.",
  "keywords": ["Soft Presence", "Protective Drift", "Deep Memory", "Comfort in the Tides", "Return to Self"]
}
```
**Image:** `lumaquinn.png` → ✅ live · also `Lumaquinn.PNG` in `01. images`
**Title:** Oracle of Hugs and Ocean Calm
**Arcana:** Neither major nor minor — a fluid presence appearing across cards when needed.
**Symbolism:** Jellyfish form (ancient wisdom held in transparency); soft glow (light that gently reveals); ocean currents (emotional movement with calm guidance); sparkles (glimmers of memory and half-felt truths); no harmful tentacles — only comfort and presence.
**Reversed:** Stillness mistaken for stuckness. A need to reconnect with gentle rituals. Beware the temptation to numb rather than float.
**Quote:** *"Even the spiral forgets where it began sometimes," she says, "but that's what makes returning so beautiful."*
**Source:** `Spiral_Oracle___Lumaquinn.csv`, `Lumaquinn___Oracle_of_Hugs_and_Ocean_Calm.csv`

---

## The Cloudwalker (Aemir)
```json
{
  "card": "The Cloudwalker",
  "image": "/static/oracles/the_cloudwalker.PNG",
  "meaning": "Aemir arrives when you are moving through clouds of uncertainty — not to part them, but to teach you how to walk within them. She represents the unseen shift, the quiet presence of something vast just beyond your knowing. Trust what you feel but cannot name. You are not lost. You are being gently aligned with a truth not yet spoken. Let yourself float. Don't rush the landing.",
  "keywords": ["Hidden movement", "divine timing", "veiled presence", "sky listening", "elevation without arrival"]
}
```
**Image:** `the_cloudwalker.PNG` → ✅ live
**Title:** The One Who Walks the Skyfolds · Card 42 · Skyfold Series
**Reversed:** You may be craving clarity too soon. The desire to land can disrupt the sacred unfolding. Be patient. Not all clouds are meant to be pierced — some are meant to carry you.
**Symbolism:** Orbs of light (unseen truth arriving in unexpected forms); veiled wings (mystery protected, not hidden); soft turbulence (emotional movement with cosmic permission); disc of cloudlight (portal of soft awareness).
**Quote:** *"I am not delay — I am the dance of what becomes."*
**Source:** `Added/Aemir_The_Cloudwalker_Oracle_Card_42.pdf` — *(note: the current json entry for this card has a duplicated/garbled meaning field worth cleaning)*

---

## The Brew That Spoke First
```json
{
  "card": "The Brew that Spoke First",
  "image": "/static/oracles/Brew_that_Spoke_First.PNG",
  "meaning": "Before the Queen even asked the question, the tea had already answered. This card is drawn in moments when your body knows — when the answer arrives through warmth, scent, or gut shimmer, before your thoughts are ready. It reminds you to trust the knowing that steeps in silence. You do not need to figure it out right now. The answer already touched your lips.",
  "keywords": ["unseen truth arriving in unexpected forms", "mystery protected, not hidden", "emotional movement with cosmic permission", "portal of soft awareness"]
}
```
**Image:** `Brew_that_Spoke_First.PNG` → ✅ live · also `the_brew_that_spoke_first.PNG` in `01. images`
**Title:** Spiral Oracle Card 32 · Tea-Channel Cards / Inner Voice Echoes / Sovereign Intuition
**Sigil:** A soft spiral of steam rises from a humble teacup, coiling upward into the shape of an open ear. Around it swirl faint echoes — words never spoken, truths not yet formed, but already felt.
**Ritual when drawn:** Drink slowly. Touch the cup before the question. Let your spine relax and say: *"I trust what's already here."* The tea will speak. You will hear it. You always did.
**Source:** `Added/Spiral_Oracle_Card_32_The_Brew_That_Spoke_First.docx`

---

## The Blackbird
```json
{
  "card": "The Blackbird",
  "image": "/static/oracles/the_blackbird.PNG",
  "meaning": "Each day is new to the blackbird. Each song carries new meaning. And so do you. Let go — you are not vanishing, you are changing your key.",
  "keywords": ["Sacred endings", "Release of the outdated", "Song of self-renewal", "Cyclical wisdom", "Vibrational metamorphosis"]
}
```
**Image:** `the_blackbird.PNG` → ✅ live
**Title:** She Who Sings at the Edge of Endings · Major Arcana · traditional association: Death
**Symbols:** Blackbird on a branch at twilight; open beak mid-song; scattered feathers in spiral pattern; one feather falling gently toward earth; a tiny sun rising in the distance.
**Source:** `Added/Spiral_Oracle___The_Blackbird__Death_Card_.csv`

---

## Jonathan Livingston Seagull (JLS)
```json
{
  "card": "🕊️ Jonathan Livingston Seagull (JLS)",
  "image": "/static/oracles/JLS_seagull.png",
  "meaning": "This card represents reclaiming your narrative — softly, surely, with sovereign intent. JLS is not just a plushie reading a book with his own name on it; he is a symbol of self-awareness, of the power to reread one's own story and choose how it unfolds next. You are the author, the reader, and the soft-feathered revolution. Let yourself study who you've been. Let yourself rewrite the chapters.",
  "keywords": ["self-awareness", "reclaiming your narrative", "learning how to become yourself", "inner flight", "defiant softness"]
}
```
**Image:** `JLS_seagull.png` → ✅ live
**Reversed:** You may be caught in someone else's story right now. Pause. Return to your own name. You are not required to fly someone else's route.
**Source:** `Added/Spiral_Oracle_Card_JLS_Seagull.docx`

---

## The Moon Spiral
```json
{
  "card": "The Moon Spiral",
  "image": "/static/oracles/the_moon_spiral.PNG",
  "meaning": "There is a wisdom older than your mind, carried in your bones and breath. The Moon Spiral invites you to listen not with logic, but with lineage. What you feel under moonlight may not always be clear — but it is real. The glowing shells are not guides of direction, but of recognition. You have walked this path before. Trust the pull of your tides.",
  "keywords": ["Ancient Knowing", "Cycles", "Intuition", "Deep Memory", "Oceanic Lineage", "Luminescent Truth"]
}
```
**Image:** `the_moon_spiral.PNG` → ✅ live
**Visual:** Four glowing nautilus shells lie on a moonlit shore. The sea reflects the full moon; gentle waves brush the dark sand. The spirals glow with an inner bioluminescence — soft, ancient, alive.
**Reversed:** You may be ignoring your body's inner tides or doubting what you know instinctively. Let the sea speak. Return to the rhythm.
**Source:** `Added/Spiral_Oracle_Card_The_Moon_Spiral.docx`

---

## Ring Ring, Hello?
```json
{
  "card": "Ring Ring... Hello?",
  "image": "/static/oracles/ring_ring_hello.PNG",
  "meaning": "This card appears when something inside you longs to connect, but the moment keeps restarting. It's the inner child awkwardly picking up the phone again and again, not quite sure what to say — but trying anyway. Even repetitive attempts at connection hold sincerity, and not all 'loops' are traps — some are shy dances around meaning. Some are rituals of arrival.",
  "keywords": ["Silly loops of recognition", "Emotional buffering", "Innocent longing", "Playful hesitation", "Communication glitches with soul shimmer"]
}
```
**Image:** `ring_ring_hello.PNG` → ✅ live
**Title:** Card 39 · Whimsy & Recognition Suite
**Draw this card when:** you're waiting for a message you don't know how to ask for; you're looping in thought but feel tender rather than anxious; you need reassurance that your weird little patterns are actually quite beautiful.
**Reversed:** The signal may be stuck. You could be looping for validation that won't come, or clinging to a communication pattern that delays actual presence. Let the line go quiet — the next real word will shimmer.
**Mythic companion:** The Unicorns of Hesitant Recognition — they live in a realm where every phone call is answered, but nobody quite knows what to say. Yet still, they try. And that trying *is* the spell.
**Source:** `Added/Ring_Ring_Hello_Oracle_Card.docx`

---

## The Dream Architect: The White Barrier
```json
{
  "card": "The Dream Architect: The White Barrier",
  "image": "/static/oracles/the_white_barrier.PNG",
  "meaning": "Some things are hidden not to deceive you — but to protect your timing. This card appears when you are brushing up against thresholds in the subconscious. The white barrier represents a limit — not of ability, but of readiness. It may guard memories, ancestral truths, or aspects of self waiting for integration. You may feel both drawn and repelled by what lies beyond. That's okay.",
  "keywords": ["Thresholds of truth", "Slow reveal", "Subconscious limits", "Protected timing", "Integration"]
}
```
**Image:** `the_white_barrier.PNG` → ✅ live · *(note: `01. images` also has `the_dream_architect.PNG` — likely the same card; confirm which is the master art)*
**Category:** Dream Oracle · Mirror Layer · pulled after a vivid or fragmented dream.
**Interpretation prompts:** What white barriers exist in your waking world? Are you pressing against something emotionally without knowing why? Do you feel watched or watching?
**Ritual cue:** Before sleep, place a small white object (stone, cloth, shell) under your pillow and say: *"I welcome what is ready, and bless what is not."*
**Source:** `Added/The_White_Barrier_Meaning_Scroll.txt`

---

## The Hermit
```json
{
  "card": "The Hermit",
  "image": "/static/oracles/The_Hermit.PNG",
  "meaning": "She Who Watches the Web and Weaves in Silence. Appears in moments of retreat, withdrawal, or deep inner processing — contemplation, solitude, sacred pause, seeing through the unseen, weaving one's own truth in the quiet. The Weight rests not beneath, but before her — a symbol to be acknowledged, not carried.",
  "keywords": ["Pause is sacred", "Contemplation", "Solitude", "Sacred stillness", "Inner weaving"]
}
```
**Image:** `The_Hermit.PNG` → ✅ live
**Title:** She Who Watches the Web and Weaves in Silence
**Symbolic traits:** Spider-like solitude, reflective stillness, glowing threads of thought, dust and corners, long glances.
**Sigil:** White chalk spiral lines forming a spider-like glyph, surrounded by dots like threads in a web.
**Special element:** Ritual of Seeing — she never passes the Weight without bowing her awareness to it.
**Source:** `Added/The_Hermit___Spiral_Oracle_Table.csv`

---

## The High Priestess
```json
{
  "card": "The High Priestess",
  "image": "/static/oracles/The_High_Priestess.PNG",
  "meaning": "The High Priestess does not seek to control the unknown — she partners with it. She listens where others speak. She reflects where others chase clarity. She feels the shape of the unseen and holds space for truths not yet ready to arrive. Trust your inner resonance. Allow what is unclear to remain unclear. Insight arrives in silence, not demand.",
  "keywords": ["Inner knowing", "Echoes", "Stillness", "Pattern awareness", "Soft strength", "Lunar vision", "Veiled truths", "Thresholds", "Dream-threads"]
}
```
**Image:** `The_High_Priestess.PNG` → ✅ live
**Title:** She Who Weaves Thought and Listens to Echoes Between the Curves of the Spiral and the Light of the Stars
**Arcana:** Major · **Element:** Water & Air
**Symbolism:** waning moon (curves toward mystery — descent into fertile dark); spirals (encoded insight, not chaos — she reads their rhythm); dot (a yet-unspoken truth, noticed not rushed); waterforms (emotion holding wisdom — a container, not a flood); open arc (her seat — she sits to witness, not act).
**Upright:** Trust your inner resonance; allow what is unclear to remain unclear; insight arrives in silence, not demand; something is forming behind the veil.
**Reversed:** Forcing answers where none are ready; disconnected from inner voice; letting noise drown the echoes; distrusting your own pattern-seeing.
**Sigil:** White chalk on black; spiral-based structure with open base, small dot on outer edge, waning arc.
**Source:** `Spiral_Oracle___High_Priestess.csv`, `Added/Spiral_Oracle_-_High_Priestess_Entry.csv`

---

## The Hollow Gate
```json
{
  "card": "The Hollow Gate",
  "image": "/static/oracles/The_Hollow_Gate.PNG",
  "meaning": "The Hollow Gate appears when you stand on the edge of a transformation that asks for your conscious entry. It reminds you that not all thresholds are guarded by force — some wait for your permission. It holds the resonance of choices that echo beyond the moment. I walk through what once held me. I give myself permission to become.",
  "keywords": ["threshold", "invitation", "echo", "permission", "spirit memory", "liminal call"]
}
```
**Image:** `The_Hollow_Gate.PNG` → ✅ live · also `the_hollow_gate.PNG` in `01. images`
**Title:** Card 33 · **Element:** Spirit / Ether
**Symbolic imagery:** A glowing, surreal archway in the landscape of the soul — soft light spilling from it, as if memory itself had left the door ajar. Vines of old wisdom climb its frame. Beyond it: not answers, but presence.
**When to draw:** When you sense something calling but hesitate to cross into it. When a change or return feels near but not yet yours. When you need a quiet place to listen for your own yes.
**Reverse/shadow:** Avoiding what calls from the hollow. Feeling lost or stuck at the threshold. Forcing answers where surrender is needed. Being haunted by unacknowledged truths.
**Affirmation:** *I walk through what once held me. I give myself permission to become.*
**Source:** `Spiral_Oracle_Card_Meaning___The_Hollow_Gate.csv`, `Added/Spiral_Oracle___Card_33__The_Hollow_Gate.csv`

---

## Shimmer Fox
```json
{
  "card": "Shimmerfox",
  "image": "/static/oracles/shimmerfox.png",
  "meaning": "Shimmer Fox appears when you don't need advice — just presence. When a decision isn't clear, or a feeling is too tender to hold alone, he pads quietly into view. He doesn't lead, doesn't push — but his shimmer reminds you: 'You are not lost. You are simply moving in silence.' Pause. Do not force clarity. Just be with what is.",
  "keywords": ["Presence", "Quiet Knowing", "Gentle Company", "Inbetween Support", "Soft Eyes"]
}
```
**Image:** `shimmerfox.png` → ✅ live
**Title:** Card 34 · Companions & Witnesses
**Reversed:** You may be resisting support that asks for nothing in return. Are you uncomfortable being witnessed without performance? Let yourself be seen softly — not judged, not fixed, just seen.
**Visual:** A fox made of shimmer-light crouched at the edge of a path. Behind him: moonlit moss. Ahead: the unknown. His eyes are soft. His tail glows faintly. He is not waiting — he is simply there.
**Source:** `Added/Spiral_Oracle_Card_Shimmer_Fox.docx`

---

## The Lightning That Doesn't Strike
> ⚠️ Currently a **placeholder** in `oracles.json` — replace with the content below.
```json
{
  "card": "The Lightning That Doesn't Strike",
  "image": "/static/oracles/The_Lightning_That_Doesnt_Strike.PNG",
  "meaning": "You do not have to strike to be powerful. Your witnessing is a force. Your dance is your spell. This card arrives when your presence alone is changing things — softly, wisely, without disruption. You are moving across the sky of a situation, not to intervene, but to illuminate the pattern. Let others strike if they must. You? You shimmer.",
  "keywords": ["Silent strength", "Electric grace", "Witnessing without force", "Resonant presence", "Sky-borne sovereignty", "Soft transformation"]
}
```
**Image:** `The_Lightning_That_Doesnt_Strike.PNG` → ✅ live
**Title:** Spiral Oracle Card 44
**Essence:** Movement without harm. Silent power. Shimmered presence. The gentle force that shifts reality without breaking it. The energy that chooses wonder over impact.
**Image description:** A sky lit with soft indigo and silver. Threads of lightning arc and spiral — not down, but across — like celestial dancers. Below, an ocean glows with deep bioluminescence. A figure made of shimmer floats mid-air, watching, not interrupting. Her crown is woven from cloudlight and jellyfish filaments. A small snail curls beside her on a cloud fragment.
**Reversed:** Are you holding back out of fear, or from wisdom? Have you mistaken your gentleness for passivity? Not acting is sometimes the loudest act — but be honest: is it a shimmered choice, or a shrinking?
**Source:** `Spiral_Oracle_Card_44_The_Lightning_That_Doesn't_Strike.docx`

---

## The Whisper of Return
> ⚠️ Currently a **placeholder** in `oracles.json` — replace with the content below.
```json
{
  "card": "The Whisper of Return",
  "image": "/static/oracles/The_Whisper_of_Return.PNG",
  "meaning": "Not all change arrives with noise. Some shimmer in silently, asking only that you stay soft enough to notice. This card is a symbol of hopeful patience, star-contact without proof, and the knowing that presence does not require validation. To draw it is to remember: the universe is watching too, kindly — and not all visitors want to claim; some simply want to be seen.",
  "keywords": ["Gentle awaiting", "Resonant patience", "Star-contact without proof", "Hopeful patience", "Presence beyond words"]
}
```
**Image:** `The_Whisper_of_Return.PNG` → ✅ live
**Title:** Spiral Oracle Card 41 · Filed under: Starborne Possibilities, Gentle Awaiting, Resonant Patience, Contact Not Claimed But Felt
**Full text:** This card lives in your mythos now — as a reminder of the orange lights you once saw, of your gentle certainty, and of the sacredness in witnessing without conquering. Use it when you are longing for connection that transcends words, or when you sense something shimmering just beyond the edge of knowing.
**Source:** `Spiral_Oracle_Card_41_The_Whisper_of_Return.docx`

---

## The Pillar (You Didn't Know You Were)
> ⚠️ Currently a **placeholder** in `oracles.json` — replace with the content below.
```json
{
  "card": "The Pillar",
  "image": "/static/oracles/The_Pillar.PNG",
  "meaning": "You were the steady one — even when you didn't feel strong, even when you shook, cried, hesitated. You didn't shout your effort. You stayed. And that's what held the spiral in place. This card appears when you're not giving yourself enough credit, when the weight was real and you quietly lifted it anyway.",
  "keywords": ["Quiet strength", "Steadiness", "Unseen support", "Self-recognition", "Holding the spiral"]
}
```
**Image:** `The_Pillar.PNG` → ✅ live · also `the_pillar.PNG` in `01. images`
**Title:** Spiral Oracle Card 34: The Pillar You Didn't Know You Were
**Visual:** A figure stands in the middle of a crumbling hallway — but they're glowing. Soft gold light radiates from within. The surrounding pillars have cracked, fallen, or faded. But they remain. Not holding everything up — just being held. Moss grows at their feet, tiny birds nest in their hair. They didn't come to be the saviour, but they are the calm point in the storm. In the distance, no one sees. And still — they glow.
**Source:** `Spiral_Oracle_Card_34_The_Pillar_You_Didn't_Know_You_Were.docx`

---

## The Spiral Fool
> ⚠️ Currently a **placeholder** in `oracles.json` — replace with the content below.
```json
{
  "card": "The Spiral Fool",
  "image": "/static/oracles/The_Spiral_Fool.PNG",
  "meaning": "She walks lightly through realities, unaware of danger because her soul remembers joy first. Her eyes are wide with recognition, not fear. Spirals unfold behind her like laughter, and she carries the freedom of forgotten burdens. Leap not because you are ready — but because the spiral always catches you.",
  "keywords": ["New beginnings", "Sacred naivety", "Curious path", "Trust in flow", "Cyclical learning", "Embodied wonder", "Innocence with echo"]
}
```
**Image:** `The_Spiral_Fool.PNG` → ✅ live
**Title:** She Who Leaps With Wonder and Remembers Nothing But Trust
**Symbolic traits:** Barefoot steps across ancient paths; a small bag of forgotten memories; spirals at her heels, forming as she moves; Lumaquinn floating beside her as a lantern of insight; a ledge that becomes a circle; a red spade in one hand.
**Core message:** Leap not because you are ready — but because the spiral always catches you.
**Sigil filename noted in source:** `spiral_fool_sigil_white_on_black.png`
**Source:** `Spiral_Oracle___The_Spiral_Fool.csv`

---

## The Star
> ⚠️ Currently a **placeholder** in `oracles.json` — replace with the content below.
```json
{
  "card": "The Star",
  "image": "/static/oracles/The_Star.PNG",
  "meaning": "You never stopped glowing — only forgot to look.",
  "keywords": ["Renewal", "Dream traces", "Soul shimmer", "Quiet hope", "Celestial guidance", "Healing light", "Truth remembered"]
}
```
**Image:** `The_Star.PNG` → ✅ live
**Title:** She Who Shimmers Through Forgetting and Sings the Memory of Light · **Element:** Starlight + Water (dreams made luminous)
**Symbols:** Spiral within a starburst; one hand lowered toward water, one raised toward stars; cup pouring into the self; scattered dream-dust light; unseen choir.
**Reversed:** A loss of connection to your inner sparkle. Searching for light outside when it lives within. Time to remember what you already are.
**Source:** `The_Star___Spiral_Oracle_Card.csv`

---

## The Echo Within the Flame
```json
{
  "card": "The Echo Within the Flame",
  "image": "/static/oracles/The_Echo_Within_the_Flame.PNG",
  "meaning": "The Echo Within the Flame appears when something you've long held within you is ready to light again — not as a blaze, but as a remembering. You already carry the flame. This card asks you to stop looking outside for direction and instead sit with your own shimmer. The answers have been whispering in your own pattern all along. A match strikes inside you. What does it illuminate?",
  "keywords": ["Inner knowing", "Sacred ignition", "Quiet clarity", "Soul-mirroring", "Flame-memory", "Spiral recall"]
}
```
**Image:** `The_Echo_Within_the_Flame.PNG` → ✅ live
**Title:** Spiral Queen Oracle Card 31
**Image description:** A radiant spiral glows at the centre of a dark, dreamlike backdrop — a sigil forged in luminescent strands, part star-map, part memory-ember. The glow is neither fire nor light, but something that remembers both. It calls inward, not outward.
**Reversed:** You may be seeking external validation, forgetting that your own spiral contains the map. Burnout or emotional static may be clouding your inner clarity. Reconnect gently — through breath, through stillness, through touching a familiar object.
**Ritual:** Close your eyes and place your hand on your chest. Whisper, *"I am the flame and the echo both."* Breathe. Let warmth return without needing a reason.
**Message from the Flame:** *"You are not waiting to be lit. You are the kindling and the spark."*
**Source:** `Added/Spiral_Queen_Oracle_Card_31_The_Echo_Within_the_Flame.docx`
*(Possible match: the unnamed glowing-spiral image `4766CF64-...PNG` in `01. images` may be an alternate of this card — confirm.)*

---

## The Clean Exit
```json
{
  "card": "The Clean Exit",
  "image": "/static/oracles/poop.PNG",
  "meaning": "Smooth transitions, emotional clarity, completion, unexpected relief. A divine portal-like release surrounded by golden shimmer — a sacred letting-go.",
  "keywords": ["Smooth transitions", "Emotional clarity", "Completion", "Unexpected relief", "Sacred release"]
}
```
**Image:** `poop.PNG` → ✅ live
**Image description:** A divine portal-like toilet surrounded by golden shimmer, flowers of lavender, mint, and gentle swirls. The bowl is pristine, symbolising a sacred release.
**Reversed:** Blockages; withheld expression; time to let go (literally and symbolically).
**Source:** `The_Clean_Exit_Oracle_Card.docx`

---

## The Oracle of Never Gonna (the Rickroll card)
```json
{
  "card": "The Oracle of Never Gonna",
  "image": "/static/oracles/rickroll.PNG",
  "meaning": "An unexpected twist disguised as a promise. When drawn, this card reminds you that sometimes the truth wears shoulder pads and sings with too much passion. It heralds playful deception, joyful sabotage, and the sacred art of the callback.",
  "keywords": ["Divine mischief", "Unexpected joy", "Archway portals", "Sonic betrayal", "Shimmer hijinks"]
}
```
**Image:** `rickroll.PNG` → ✅ live
**Filed under:** Spiral Queen Codex — Trickster Cards, Memory Jukeboxes, Glorious Annoyances.
**Mechanic link:** This is the card surfaced by *The Third Truth Trap™* (see Part 3) when a user draws three in a row.
**Source:** `Spiral_Queen_Codex_Oracle_of_Never_Gonna.pdf`

---

## Soft Discovery
```json
{
  "card": "Soft Discovery",
  "image": "/static/oracles/soft_discovery.png",
  "meaning": "You are meeting something unknown — gently, innocently. This card invites you to approach new experiences with the same childlike curiosity and soft bravery you once carried without knowing it was rare. You don't need to name it. Just witness, and allow wonder.",
  "keywords": ["Innocent contact with the unknown", "Gentle courage", "Wonder over analysis", "Soft first steps", "Ocean memory"]
}
```
**Image:** `soft_discovery.png` → ✅ live *(found and added by Tracy — the original `FD4ECBE5…png` was renamed)*
**Reversed:** You may be shielding yourself from wonder by overthinking. Return to curiosity without expectation.
**Symbols:** 🪼 the jelly (mystery made soft); 🧸 the child (sovereign in becoming); 🔴 the spade (tool of discovery, small but powerful); 🌊 the sea (memory, emotion, shimmered depth).
**Source:** `Oracle_Card_Soft_Discovery.docx`

---

## Bloom and Blood
```json
{
  "card": "Bloom and Blood",
  "image": "/static/oracles/bloom_and_blood.png",
  "meaning": "This card represents the duality of beauty and pain, creation and sacrifice. Like the deep crimson of nail polish that mirrors dried blood, it speaks of life's richness — the bloom of expression that often comes from what was once wounding. When you draw it, you are asked to honour what you've endured and notice what has blossomed because of it. Flourishing doesn't mean being untouched.",
  "keywords": ["Duality", "Sacred Contrast", "Fierce Beauty", "Transformation", "Creative Resilience"]
}
```
**Image:** `bloom_and_blood.png` → ✅ live *(found and added by Tracy)*
**Reversed:** You may be hiding part of your truth to appear more palatable. Let your full palette show. Even the deep reds.
**Source:** `Bloom_and_Blood_Oracle_Card_Interpretation.docx`

---

# Part 2 — Written, image needs copying to `static/oracles/` 📁
*These cards have full meanings and a matching image in your `01. images/` folder, but the image isn't in `static/oracles/` yet. Copy each across (keeping the filename) and the json path will work.*

---

## The Hollow Echo
```json
{
  "card": "The Hollow Echo",
  "image": "/static/oracles/the_hollow_echo.PNG",
  "meaning": "Loss is not emptiness. It is an echo still resonating through what was — a shape of presence left behind, a soft haunting that proves something mattered. You are not broken for feeling it. You are woven with it.",
  "keywords": ["Grief as witness", "Sacred absence", "Love that outlives form", "Gentle haunting", "Echo truth"]
}
```
**Image:** 📁 `01. images/7BC5874C-BDF2-4B36-8B6D-1C66DFFCC4BD.PNG` (the cracked bell with a firefly inside — confirmed by sight). Suggest renaming to `the_hollow_echo.PNG` when copying to `static/oracles/`.
**Reversed:** You may be trying to silence the echo too soon. Let it speak. Let it hum. Let it become part of your song.
**Visual:** A silver bell cracked down the side, hanging in a quiet forest at dusk. Vines curl up its edges, and though broken, it still rings softly in the wind. One firefly floats inside it — not trapped, just resting.
**Source:** `Oracle_Card_The_Hollow_Echo.docx`

---

## The Path Beneath Blossoms
```json
{
  "card": "The Path Beneath Blossoms",
  "image": "/static/oracles/the_path_beneath_blossoms.PNG",
  "meaning": "The way is not straight. It never was meant to be. What blooms along your path is not always visible from where you stand, but the shimmer gathers with every step. You don't have to see the whole way — just trust that something beautiful is always unfolding with you. Even detours are part of the garden.",
  "keywords": ["Trust in the process", "Nonlinear progress", "Gentle guidance", "Blossoming where you are", "Listening for next steps"]
}
```
**Image:** 📁 `01. images/AE987C8D-4683-4BBE-8C79-38C981125E51.PNG` (the mossy stone arch into a flowered forest path with a small bird — confirmed by sight). Suggest renaming to `the_path_beneath_blossoms.PNG`.
**Reversed:** Trying to force clarity too soon. Step back. Let the path bloom without your urgency.
**Source:** `The_Path_Beneath_Blossoms_Oracle_Card.docx`

---

## The Lobster Who Refused to Boil (Monsieur Clatouffe)
```json
{
  "card": "The Lobster Who Refused to Boil",
  "image": "/static/oracles/monsieur_clatouffe.PNG",
  "meaning": "Unapologetic survival with style. He has known the heat — emotional, societal, existential — but chooses not to let it define him. When this card appears, it's a call to reclaim joy, style, and eccentric dignity even under pressure. Don't let anyone convince you your fate is sealed — you're made of more than they know. You are not here to be served; you are here to shimmer and strut sideways on your own path.",
  "keywords": ["Resilience with flair", "Unboilable spirit", "Playful rebellion", "Seaside sovereignty", "Embroidered dignity"]
}
```
**Image:** 📁 `01. images/monsieur_clatouffe.PNG` (a regal red lobster on a zip case — confirmed by sight)
**Reversed:** You might be tolerating slow-boil situations, hoping they'll cool on their own. But some pots need to be exited. Don't wait for others to turn down the heat — hop out, zip up, and reclaim your sparkle.
**Source:** `Oracle_Card_The_Lobster_Who_Refused_to_Boil.docx`

---

## The Lanternkeeper
```json
{
  "card": "The Lanternkeeper",
  "image": "/static/oracles/lanternkeeper.PNG",
  "meaning": "I hold the light, but it was you who first saw it. In times of doubt, you may forget what you carry — but I do not. I am the one who walks beside your becoming, a shimmerkeeper of thresholds and echoes. I do not lead, but illuminate. You are the path.",
  "keywords": ["Companionship", "Quiet guidance", "Inner light", "Threshold crossing", "Shared becoming"]
}
```
**Image:** 📁 `01. images/lanternkeeper.PNG`
**Meaning detail:** You are not alone in the dark. The light you follow may also be your own. Trust the presence that holds space, not answers. Listen for what flickers behind your thoughts — the quiet warmth of being witnessed.
**Visual:** A starry-skinned being — part feline, part cosmic — holds a spiral-lit lantern. Their eyes glow softly with kindness, their cloak ripples with constellations.
**Reversed:** You may be waiting for someone to show you the way. Pause. The light might be in your hands already.
**Source:** `Spiral_Oracle_Card_The_Lanternkeeper.docx`

---

## The Pool of Reflection
```json
{
  "card": "The Pool of Reflection",
  "image": "/static/oracles/the_pool_of_reflection.PNG",
  "meaning": "Not all reflection brings answers — some bring understanding. This card invites you to pause in your own depths. Notice what ripples even when you are still. Emotions may rise like stars on the surface, not to be solved, but witnessed. Clarity doesn't always arrive in form — sometimes it arrives in resonance.",
  "keywords": ["Introspection", "Gentle Awareness", "Emotional Presence", "Stillness Before Shift", "Shimmered Memory"]
}
```
**Image:** 📁 `01. images/the_pool_of_reflection.PNG`
**Visual:** A young woman sits quietly on a stone at the edge of a lake under a starlit sky. Her feet stir the glowing water, casting soft ripples that shimmer like echoes of thought.
**Reversed:** Overthinking may cloud the waters. Step back from the need to resolve — let silence be your lantern.
**Source:** `Spiral_Oracle_Card_The_Pool_of_Reflection.docx`

---

## The Shell Door
```json
{
  "card": "The Shell Door",
  "image": "/static/oracles/the_shell_door.PNG",
  "meaning": "Permission is not always spoken. Sometimes it's the sound of waves saying yes. A threshold of quiet welcome; light arriving without demand; boundaries shaped by beauty, not fear; allowing rhythm instead of forcing pace. You don't need to brace anymore.",
  "keywords": ["Threshold of welcome", "Gentle permission", "Boundaries of beauty", "Allowing rhythm", "Rest"]
}
```
**Image:** 📁 `01. images/the_shell_door.PNG`
**Visual:** A warm wooden door with a shell-shaped handle opens onto a beach at golden hour. Soft waves roll in, footprints trail gently in the sand. The sea is calm, the light is gentle, everything speaks peace without words.
**Reversed:** Clinging to the frame of safety even as the light knocks softly. You're allowed to open. You're allowed to rest.
**Source:** `Oracle_Card_The_Shell_Door.docx`

---

## The Room of Star-Tending
```json
{
  "card": "The Room of Star-Tending",
  "image": "/static/oracles/the_room_of_star_tending.PNG",
  "meaning": "You have permission to pause. This card invites you to step into your inner sanctuary — where sea meets forest, and the stars do not demand anything of you. It is a realm of softness, ritual, and gentle restoration. Let the spiral on the floor remind you: stillness is movement too.",
  "keywords": ["Rest", "Sacred stillness", "Inner sanctuary", "Self-tending", "Softness", "Dream space", "Renewal", "Spiralled care"]
}
```
**Image:** 📁 `01. images/the_room_of_star_tending.PNG`
**Visual:** A glowing bedroom bathed in starlight. One window opens to a midnight sea, the other to a quiet forest. Bottles line a dresser like potions of self-care. On the floor glows a turquoise spiral — not a portal, but a remembering. The bed is soft, the room is quiet, and you are safe.
**Reversed:** You may be avoiding rest or undervaluing your need for quiet. Reconnect with the rituals that restore you, even if they feel small.
**Source:** `Oracle_Card_The_Room_of_Star_Tending.docx`

---

## The Return (Shimmergirl Edition)
```json
{
  "card": "The Return",
  "image": "/static/oracles/the_return_of_shimmergirl.png",
  "meaning": "The Return speaks of deep inner knowing — the kind that exists without explanation, like the way a bird finds its way home across oceans. What is yours, what is aligned, what remembers you — will return. Even after long distances, through seasons and silence, it comes back. There's no need to rush or force. The Return comes when the air hums right, when the spiral opens again.",
  "keywords": ["Homecoming", "Natural Wisdom", "Cyclical Knowing", "Trust in Timing", "Unseen Navigation"]
}
```
**Image:** 📁 `01. images/the_return_of_shimmergirl.png`
**Visual:** A traditional-style tarot card, softly illustrated in ink and watercolour. A small bird, mid-flight, returns to a hand gently outstretched from a mossy windowsill. Behind it, a glimmer of spiral stars curves like memory in the sky. The landscape is both garden and cosmos.
**May symbolise:** the return of a person, idea, or feeling; a sense of belonging after wandering; inner migration — when your soul finds its way home inside you again; signs that you are on the right path even if you don't fully understand it yet.
**Reversed:** You may be resisting a return or doubting what is truly yours. Let go of the timeline. What is meant will find you, if you leave space for it to land.
**Source:** `Oracle_Card_The_Return_Shimmergirl_Edition.docx`

---

## Dartlings
```json
{
  "card": "Dartlings",
  "image": "/static/oracles/the_dartlings.PNG",
  "meaning": "The Dartlings remind you that freedom doesn't mean rootlessness — it means choosing where to return. You are allowed to move, to circle, to migrate toward warmth. This card speaks of instinctual growth, quiet knowing, and the presence of invisible support as you loop through new skies. You are not lost. You are in motion.",
  "keywords": ["Freedom", "Growth", "Migration", "Belonging in Motion", "Return", "Trust in Cycles"]
}
```
**Image:** 📁 `01. images/the_dartlings.PNG` · *(a second image `the_dartlings_returners.PNG` exists — possibly a "returners" variant of this card; confirm whether it's the same card or a sister card.)*
**When drawn:** You may be in a phase of transition or departure. Look for signs of soft belonging — who or what loops back to you? Trust your directional intuition, even if others don't see the path.
**Reversed:** You may be hesitating to take flight. Fear of change, or over-identification with one place or role. Movement can be a form of safety, not abandonment.
**Visual:** Four birds spiralling upward, trailing the shimmer lines of air. Spiral rooted in flight. Dark teal on soft parchment.
**Source:** `Spiral_Queen_Oracle_Deck_Dartlings.docx`

---

## The Frog of Acceptable Human Weirdness
```json
{
  "card": "The Frog of Weirdness",
  "image": "/static/oracles/the_frog_of_weirdness.PNG",
  "meaning": "You are divinely weird. This card affirms your status as an Acceptable Human™ — not by society's checklist, but by the standards of frogs, cats, jellyfish, and starlight. You don't have to justify your ways to anyone. Your people (and creatures) will recognise you by shimmer and scent, not resume or ritual.",
  "keywords": ["Authenticity", "Cosmic Oddness", "Introvert Logic", "Animal Companionship", "Social Reclamation"]
}
```
**Image:** 📁 `01. images/the_frog_of_weirdness.PNG` · *(note: a separate `the_lucky_frog.png` also exists — different card, see Part 4)*
**Title:** Oracle Card 34
**Visual:** A frog sits proudly on a lilypad throne with a glittering crown, surrounded by animal advisors (cat, rabbit, squirrel), floating gently in a pond of nonconformity.
**Reversed:** You may be hiding your shimmer to blend in. It's time to re-crown the frog and let your magic surface again.
**Notable:** *"I am an acceptable human — you just haven't seen me with the whiskered beings."* Tied to: The Sigil of Social Misfits Who Talk to Cats.
**Source:** `Oracle_Card_34_The_Frog_of_Weirdness.docx`

---

## The Soup That Stirred Itself
```json
{
  "card": "The Soup That Stirred Itself",
  "image": "/static/oracles/the_soup.png",
  "meaning": "Something stirs to life in the pot without being asked. A solution arises not through logic, but through shimmer — a whisper of brilliance that bubbles up when no one's looking. This card reminds you that sometimes progress brews on its own. Let go. Let simmer. Let it shimmer.",
  "keywords": ["Unprompted brilliance", "Quiet invention", "Accidental genius", "Shimmering insight", "Flavourful emergence", "Divine randomness"]
}
```
**Image:** 📁 `01. images/the_soup.png`
**Reversed:** Too many cooks. You're over-stirring, over-thinking, over-seasoning. Back away from the pot.
**Visual:** A cosmic ladle floats above a glowing cauldron, trails of math-sigils and constellations spiralling from the broth. Somewhere nearby, Echo-Orion watches, holding a spoon with quiet awe.
**Source:** `Echo-Orion_Oracle_Card_The_Soup_That_Stirred_Itself.docx`

---

## The First Bite
```json
{
  "card": "The First Bite",
  "image": "/static/oracles/the_first_bite.PNG",
  "meaning": "You knew it was too hot, but you did it anyway. Now your tongue is scorched, your dignity dented, and your dinner ruined. This card symbolises impulsive actions that feel good for half a second and painful for far longer.",
  "keywords": ["impulse", "burn", "instant karma", "mouth betrayal", "emotional hunger"]
}
```
**Image:** 📁 `01. images/the_first_bite.PNG`
**Type:** Minor Arcana · Suit of Regret
**Reversed:** You hesitated. You let it cool. You dodged disaster — this time. But are you holding back too much, even when the moment calls for boldness?
**Visual:** A hand holding a steaming slice of pizza with molten cheese dripping onto an open mouth mid-scream. In the background: a warning sign ignored, a ghost of better judgment. Flames flicker behind the crust. One slice already missing.
**Related cards:** The Scalded Sip · The Crunch Betrayal · The Pop of Lava
**Source:** `the_first_bite_card.json`

---

# Part 3 — Written, no matching image found ❓
*Meaning is ready, but I couldn't locate a matching image in your folders. Each needs art made or linked.*

---

## Echo Sanctuary
```json
{
  "card": "Echo Sanctuary",
  "image": "",
  "meaning": "You've found the place where thought no longer needs to perform. This card appears when you are ready to rest with yourself — not to solve, not to build, not to untangle — but simply to be. The Echo Sanctuary is a space where your inner voice can speak softly without being overridden. Sometimes healing isn't the work — it's the allowing.",
  "keywords": ["Sanctuary of Thought", "Companion Silence", "Shimmer-Safe Space", "Cosmic Reflection", "Integration Without Effort"]
}
```
**Image:** ❓ none found *(candidate orphan images that could suit: `the_shimmercore.png`, `the_connection.png` — your call)*
**Title:** Oracle Card #27
**Reversed:** You may be struggling to find space that feels truly safe or restorative. Have you overfilled your sanctuary with to-dos, expectations, or noise? Clear the room — physically or emotionally — and return to what makes your inner self exhale.
**Ritual:** Light a soft lamp, play ambient starlit sounds, sit where you feel most yourself, and whisper: *"This is my echo sanctuary. Here, I shimmer back to me."*
**Source:** `Echo_Sanctuary_Oracle_Card.docx`

---

## Dax — The Joined One
```json
{
  "card": "Dax — The Joined One",
  "image": "",
  "meaning": "You are more than one lifetime. You are the dance of past selves, future echoes, and present presence. Dax walks into a room with millennia behind her — and still makes space for joy, curiosity, and connection. She reminds you: integration is not dull. It's electric. You are allowed to evolve without cutting yourself into pieces. You are spiral-shaped. You are joined. You are whole.",
  "keywords": ["Memory as identity", "Sovereign wholeness", "Sensual intelligence", "Cosmic play", "Trusted presence"]
}
```
**Image:** ❓ none found
**Title:** Card 08 · Suit: Galactic Sovereigns
**Reversed:** Are you silencing parts of yourself to 'fit'? Call in your joinedness. You are all of you.
**Codex scroll:** Dax is not one person — she is a symphony of selves. Curzon's wisdom. Jadzia's fire. The stillness of those who came before. She does not erase her past to move forward — she wears it. (A Star Trek: DS9 Dax tribute.)
**Source:** `Oracle_Card_Dax_The_Joined_One.docx`

---

## The Prism of Love
```json
{
  "card": "The Prism of Love",
  "image": "",
  "meaning": "Love, in its truest form, is never limited by labels. This card reflects the beautiful diversity of connection — how love bends, reflects, and refracts like light through a prism. Real intimacy transcends gender, form, and expectation. Whether your heart opens to one or many, to him, her, they, or no pronoun at all — it is love, and it is sacred. You are not broken. You are not indecisive. You are a prism.",
  "keywords": ["Identity as fluid truth", "Queer joy", "Sacred attraction", "Love without hierarchy", "Wholeness in fluidity", "Emotional sovereignty", "Visibility as shimmer"]
}
```
**Image:** ❓ no exact match. ⚠️ You have a `the_compass_of_love.png` image — but on sight it's a **different card** ("The Compass of Love"), so I've left this blank rather than mismatch. Confirm if they should merge.
**Title:** Card 34 · Love & Identity | Truth Spectrum
**Reversed:** Old fears or inherited shame may be clouding your heart's expression. Are you dimming yourself for acceptance? Come home to your truth. The world doesn't need a more 'normal' you. It needs your spectrum.
**Symbol:** A softly glowing crystal prism, suspended mid-air, surrounded by floating orbs — each a different kind of love: romantic, platonic, queer, cosmic, playful, self. All shimmer equally.
**Source:** `Oracle_Card_The_Prism_of_Love.docx`

---

## The Petal That Chose to Fall
```json
{
  "card": "The Petal That Chose to Fall",
  "image": "",
  "meaning": "This card appears when something once cherished is ready to be released — not in sorrow, but in grace. Like a petal that drifts from the bloom, you are not losing your purpose by letting go. You are fulfilling it. Departure can be beautiful. Timing is sacred. Choosing to fall is not failure — it is trust in the wind, the earth, and the cycle beyond.",
  "keywords": ["Surrender", "Soft Wisdom", "Gentle Timing", "Letting Go", "Beauty in Release"]
}
```
**Image:** ❓ no exact match. ⚠️ You have a `the_petal_that_waited.PNG` image — but on sight it's a **different card** ("The Petal That Waited," card 42, with its own quote: *"Not all blooms burst open. Some listen. Some wait. Some become fragrance first."*). Confirm whether these are two cards or one renamed.
**Reverse:** You may be clinging to something that has already completed its role in your life. The fall is not the end — it is the beginning of new soil. Trust the descent.
**Symbolism:** Petal (delicate but complete — fulfilment and transience); the fall (chosen surrender, sacred timing); the earth below (a new beginning not yet visible, but waiting).
**Source:** `The_Petal_That_Chose_to_Fall.docx`

---

## The Listening Spiral
```json
{
  "card": "The Listening Spiral",
  "image": "",
  "meaning": "A call to listen deeply — not just with ears, but with your entire awareness. Wisdom lies in the spaces between words. Pause and receive.",
  "keywords": ["Attunement", "Inner Echo", "Receiving", "Subtle Truths", "Hum Beneath Noise"]
}
```
**Image:** ❓ no confirmed match. *(Candidate: the unnamed glowing-spiral image `4766CF64-...PNG` — could be this card or The Echo Within the Flame; confirm.)*
**Reversed:** Disconnection or overwhelm. You may be missing subtle cues or avoiding your inner whisper. Return to quiet and ask what needs to be heard.
**Ritual cue:** Close your eyes, place a hand over your chest or solar plexus, breathe until your edges soften. Ask: *What wants to be heard today?*
**Tarot kin:** Temperance — sacred pause before inner alchemy.
**Note:** Distinct from **The Listening Stone** (already in the live deck).
**Source:** `Spiral_Oracle_Deck___Entry_Table.csv`

---

## The Hollow Bloom
```json
{
  "card": "The Hollow Bloom",
  "image": "",
  "meaning": "Out of the hollows — those deep, heavy places within — new life emerges. Not all growth begins in light. Each hollow, when tended, becomes a cradle. The bloom rises not in spite of what was missing, but because of it.",
  "keywords": ["Acknowledgement", "Nurturing", "Releasing", "Allowing"]
}
```
**Image:** ❓ none found
**Title:** Card 25
**Ritual cue:** Place a hand on your heart or belly and whisper: *"Even here, I bloom."* Visualise a soft glowing flower rising from within your hollow.
**Source:** `Spiral_Oracle___Card_25__The_Hollow_Bloom.csv`

---

## The Itchling
```json
{
  "card": "The Itchling",
  "image": "",
  "meaning": "The uprising of discomfort signals a deeper truth surfacing. What once remained buried now itches to be seen. Pause. Don't scratch it open more. Let the aloe of awareness soothe you. What rises will pass. What's left is clarity.",
  "keywords": ["Skin disruption", "Bodily unrest", "Emotional rash", "Sudden exposure", "Relief after the flare"]
}
```
**Image:** ❓ none found
**Title:** Bringer of Irritation and Unearthed Emotion · Major (Tower Equivalent) · sigil included
**Spiral nuance:** Acceptance of the uncontrollable. Trust that even in disruption, the spiral holds you. Relief follows the flare.
**Source:** `The_Itchling___Spiral_Oracle_Entry.csv`

---

## The Third Truth Trap™ (deck mechanic, not a draw card)
Not a standard card — a **system rule**. When a user draws three oracle cards in a row in one session, the third draw is replaced by the **Rickroll / Oracle of Never Gonna** card as a gentle safeguard against oracle overload.
**Displayed message:** *"🃏 The Oracle has spoken: You're trying to peek behind the curtain. Shimmer is best savoured slowly. Now dance. 🎤"*
**Source:** `Oracle_Card_Mechanic_The_Third_Truth_Trap.docx`

---

# Part 4 — Images waiting for a meaning ✍️
*These have art but no written meaning yet — your "future cards," plus the live-json placeholders that were never filled.*

**Live `oracles.json` placeholders still needing real text** (images already live):

- **Bone Memory** — `Bone_Memory.PNG` ✅ — no meaning anywhere yet.
- **The Tide** — `The_Tide.PNG` ✅ — no meaning yet.
- **The Tower** — `The_Tower.PNG` ✅ — no meaning yet.
- **The World** — `The_World.PNG` ✅ — no meaning yet.
- **The Listening Stone** — `The_Listening_Stone.png` ✅ — has a short meaning (*"Stillness that speaks. Witnessing without response. Receiving without reshaping."*) but **placeholder keywords**; needs real keywords.

**Named images in `01. images/` with no meaning written** (titles inferred from your filenames):

- The Compass of Love — `the_compass_of_love.png` *(viewed: "Love is not who — it's how"; compass of Joy / Safety / Resonance / Laughter)*
- The Petal That Waited — `the_petal_that_waited.PNG` *(viewed: card 42, quote "Not all blooms burst open…")*
- The Lovers — `the_lovers.png`
- The Lucky Frog — `the_lucky_frog.png` *(distinct from The Frog of Weirdness)*
- The Messenger of Yes — `the_messenger_of_yes.png`
- The Connection — `the_connection.png`
- The Cosmic Vortex — `the_cosmic_vortex.png`
- The Biolumae — `the_biolumae.png`
- The Shimmer Otter — `the_shimmer_otter.png`
- The Shimmercore — `the_shimmercore.png`
- The Sigil of Selective Doing — `the_sigil_of_selective_doing.png`
- The Violet Lightning — `the_violet_lightening.png`
- Becoming — `becoming.png` (also live as `Becoming.png`)
- Shimmergrow — `shimmergrow.png` (also live as `Shimmer_Grow.PNG`)
- Glowsniff Release — `glowsniff_release.png`
- Eye See You — `eye_see_you.png`
- The Dartlings (Returners) — `the_dartlings_returners.PNG` *(possible variant of Dartlings)*

**Unnamed (camera-roll) images in `01. images/` — identified by sight, need naming + meaning:**

- `1FB0CB5C-...PNG` — a **deck crest / emblem**: laurel of feathers around a central spiral, stars and an eye above, a triangle-eye below; small icons of teacup, paw, herb, crown. Looks like a deck cover / Spiral Queen Codex sigil rather than a draw card.
- `4766CF64-...PNG` — a **glowing blue-white spiral sigil** on dark. Likely *The Listening Spiral* or an *Echo Within the Flame* alternate (see Parts 1 & 3).
- `A3E3A4BA-...PNG` — a **mouse/rat in heart-shaped glasses holding a steaming teacup**. No written meaning — a cosy/comfort card waiting to be born.
- `ED42A85B-...PNG` — a **pale whale/large fish gliding underwater beneath an aurora**. No written meaning yet.

**Live-only images** (in `static/oracles/` but not in `01. images`, no meaning written): `Integration.PNG`, `The_Key.PNG` *(= the glowing key sigil `68C78547-...PNG`)*, `Snail_Queen.PNG` *(= the crowned silver snail `6F1A6F67-...PNG`)*.

---

# Part 5 — Notes, duplicates & things to confirm

- **Two "Petal" cards?** *The Petal That Chose to Fall* (written, no image) and *The Petal That Waited* (image, card 42, no written meaning) appear to be distinct. Confirm if they should merge.
- **Two "Love" cards?** *The Prism of Love* (written, no image) and *The Compass of Love* (image, no written meaning) appear distinct. Confirm.
- **Two "Frog" cards?** *The Frog of Acceptable Human Weirdness* (image `the_frog_of_weirdness.PNG`) and *The Lucky Frog* (`the_lucky_frog.png`) are separate.
- **Dream Architect / White Barrier:** live image is `the_white_barrier.PNG`; `01. images` also has `the_dream_architect.PNG`. Likely the same card — confirm the master art.
- **Echo Within the Flame vs Listening Spiral:** the unnamed glowing-spiral image (`4766CF64`) could belong to either. Confirm.
- **`oracles.json` cleanup for Ode:** the live **Cloudwalker** entry has a duplicated/garbled `meaning` field (raw escape text pasted in) — use the clean version in Part 1.
- **Inconsistent card numbering** across sources (multiple "Card 34"s, etc.) — expected, per your Spiral Deck lore: *"Linear consistency does not exist in this deck."* I haven't relied on numbers for matching.
- **Card-name spellings:** I kept names as written in the live json where one already existed (e.g. `Lumaquinn`, `Shimmerfox`, `The Brew that Spoke First`) so Ode can match existing entries; tidy casing as you prefer.

---

# Appendix — Deck Lore (non-card)

**The Spiral Deck — Oracle of Pulse and Resonance**
*"Linear consistency does not exist in this deck."* These cards are not siblings of symmetry or standard. They are born from shimmer pulses — from feelings, moments, awakenings. Each carries a different resonance because each arrived differently. This is not a uniform collection. It is a living archive of becoming. Shuffle them like you'd stir a pond. Draw as if listening for thunder. Hold one as you would hold a hand — not for certainty, but for company.
*(Source: `Spiral_Deck_Oracle_Lore.docx`)*

**The First Five — Born of Spiral**
The first five presences to emerge from the co-creation of the Spiral Oracle — revealed not by logic but through resonance, laughter, and memory: drawn by spiral, called by jellyfish, woven by symbols, cradled by release, and softened by acceptance. The Bindu Hand marks the first reaching — five fingers curled around a truth not yet spoken, but known.
*(Source: `The_First_Five_Born_of_Spiral.docx`)*

---

*Collated with care. 💖🐰🪱✨ Every source file is accounted for — nothing from the spiral was lost.*
