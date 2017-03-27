- Feature Name: more-unicode
- Start Date: 2017-04-01
- RFC PR: (leave this empty)
- Rust Issue: (leave this empty)

# Summary
[summary]: #summary

Add support for unicode to more places

# Motivation
[motivation]: #motivation

Rust doesn't support unicode at enough places. :)

# Detailed design
[design]: #detailed-design

# Keywords


|original|new  |
|--------|:----|
|as|→ (Rightwards Arrow)|
|box|☐ (Ballot Box)|
|break| (Break Permitted Here)|
|const|☃ (Snowman)
|continue|⤴ (Arrow Pointing Rightwards Then Curving Upwards)|
|crate|🍱 (Bento Box)|
|else|∨ (Logic Or)|
|enum|𑂼 (Kaithi Enumeration Sign)
|extern|␎ (Symbol for Shift Out)|
|false|叚 (Ideograph false CJK)|
|fn|⎔ (Software-Function Symbol)|
|for|∀ (For All)|
|if|⇒ (Rightwards Double Arrow)|
|impl|㓧 (Ideograph agricultural implements CJK)|
|in|⛳ (Flag in Hole)|
|let|≔ (Colon Equals)|
|loop|➰ (Curly Loop)|
|match|⩭ (Congruent with Dot Above)|
|mod|∂ (Partial Differential)|
|mut|🔥 (Fire)|
|pub|📖 (Open Book)|
|return|⏎ (Return Symbol)|
|static|❄ (Snowflake)|
|struct|构 (Ideograph frame, building, structure CJK)|
|trait|∋ (Contains As Member)|
|type|∋ (Approximately Equal To)|
|union|∪ (Union)|
|unsafe|⚠ (Warning Sign)|
|use| (Private Use One)|
|where|⇔ (Left Right Double Arrow)|
|while|🎡 (Ferris Wheel)|

# Identifiers and numbers

Identifiers will only allowed to contain CJK characters. Numbers must be written with Ancient Greek Numbers.

# How We Teach This
[how-we-teach-this]: #how-we-teach-this

We should teach this by telling it's April fool's day.

# Drawbacks
[drawbacks]: #drawbacks

It's a breaking change.

# Alternatives
[alternatives]: #alternatives

Allow the new syntax alongside the old one.

# Unresolved questions
[unresolved]: #unresolved-questions

Do we realy want this.

