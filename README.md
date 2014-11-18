# Coco/R

Coco/R is a compiler generator, which takes an attributed grammar of a source language and generates a scanner and a parser for this language. The scanner works as a deterministic finite automaton. The parser uses recursive descent. LL(1) conflicts can be resolved by a multi-symbol lookahead or by semantic checks. Thus the class of accepted grammars is LL(k) for an arbitrary k.

Coco/R was implemented in Oberon language by Hanspeter Mössenböck and others. See http://ssw.jku.at/Coco/#Oberon for more information.
