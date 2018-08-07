---
title: Alchemist
tags: srd class verbatim incomplete
---
# Alchemist
> There’s no sight more beautiful to you than a strange brew bubbling
in your laboratory’s beakers, and you consume your various creations
with abandon. Perhaps you’re fascinated with uncovering the secrets of
magic and science, or perhaps you simply like to watch volatile chemical
reactions. Regardless, you’re constantly experimenting in your lab or on
the go with inventive concoctions tweaked for any eventuality. With your
fearlessness in the face of risk, your unique path toward greatness is lined
with alchemical brews that push your mind and body to their limits.

{% assign class=site.data.classes.alchemist  %}
{% include class-table.html data=class %}

## Playing an Alchemist
Players of alchemist characters might approach gameplay in the following ways:
*  During combat, you lob bombs at your foes and harry your enemies while supporting the rest of your party with your potent elixirs.  At higher levels, you toughen your body using mutagens.
*  During social encounters, you provide knowledge and experience about alchemicalitems and related secrets, like poisons and diseases.
*  In exploration mode, you keep an eye out for trouble with your bombs at the ready while giving advice on all things alchemical and mysterious.
*  In downtime mode, you spend time in an alchemical lab brewing elixers, making bombs, and furthering your alchemical knowledge.

## Roleplaying an Alchemist
Alchemists pursue scientific innovation above all else, combining incredible powers from the natural world through the force of their keen intellect and insatiable curiosity.

**If you're an alchemist, you'll likely...**
*  Enjoy tinkering with strange formulas and alchemical reagents, often with single-minded dedication and recklessness that give others pause.
*  Get a kick out of wreaking havoc with the alchemical concoctions you've made, and enjoy watching things burn, dissolve, freeze, and jolt.
*  Endlessly experiment toward the discovery of new, more potent alchemical and magical tools.

**Others probably...**
*  Think you're at least a bit strange and don't understand your zeal for alchemy, creativity, and invention.
*  Fear that your creations are dangerous or volatile - or both.
*  Assume that if you haven't caused a catastrophe with your experimentations, you inevitably will.
*  Think that you're some kind of sorcerer or an eccentric wizard and don't understand that you're not a spellcaster.  Real spellcasters clumsily dabbling in alchemy only heighten this misconception.

# Class Features
You gain these abilities as an alchemist.  Abilities gained at higher levels list the requisite levels next to the features' names.

{% for el in class.features %}
  {% include feature.html data=el %}
{% endfor %}
