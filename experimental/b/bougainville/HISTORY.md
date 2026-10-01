Bougainville Change History
===========================

1.3 (2026-09-28)
----------------
* Renamed from "Bougainville 2019" to "Bougainville", and the keyboard ID from
  `bougainville_2019` to `bougainville`. Remove 1.2 before installing: it is a separate keyboard
* `;`, `` ` ``, `~`, `q` and `x` are now deadkeys: nothing appears until the next key, so
  no typed character has to be deleted. This makes them work in apps such as WhatsApp,
  which don't let a keyboard delete text. If the next key isn't part of a sequence, both
  characters are typed (`;` then space still gives `; `), and Backspace cancels
* New single keys for quotes and dashes, which work in every app: RAlt+[ ‘, RAlt+] ’,
  RAlt+Shift+[ “, RAlt+Shift+] ”, RAlt+- – and RAlt+Shift+- —. The older sequences
  (`''`, `""`, `--`, RAlt+Shift+< then <) still work where the app allows
* `q` then space gives a narrow no-break space (U+202F)
* `qsss` now gives sṣ (a plain s, then s with dot below) instead of ṣ alone
* Touch: curly quotes ‘ ’ “ ” added to the long-press on `.`
* Welcome page: explains the deadkeys, the new quote and dash keys, and which older
  sequences may not work in WhatsApp and similar apps
* Capitals now also work with Shift held through the trigger: `:I`, `:U`, `:V`, `:N`
  and `:C` give Ï, Ü, Ʌ, Ŋ and Ɔ, matching the existing `:A`, `:E` and `:O`
* Added capital open o: `;C` (or `:C`) gives Ɔ
* Added capital acute and nasalized vowels: `` `A `` gives Á and `~A` gives Ą (and so on for
  E, I, O, U), matching the touch layout
* All-capital double-macron vowels: `A=A` gives A͞A (and so on for E, I, O, U)
* Fixed typing `i` after ı͞ı or I͞ı, which turned the last ı into ɨ; it now adds a plain `i`
* Touch devices now use the keyboard's own touch layout, with the special letters on
  long-press of their base letter, glottals and the ` and ~ triggers on long-press of `.`,
  and dashes and hyphens on long-press of `-` in the 123 layer
* Added the supported languages (Rapoisi, Halia, Tinputz, Terei, Sibe, Petats, Naasioi) to the package
* The package now includes the welcome page, readme and licence
* The package now installs the SIL Gentium font, and the touch layout, on-screen keyboard
  and welcome page use it, so ꞌ, the double-macron vowels (a͞a) and the IPA and Greek
  letters display correctly on phones and computers without their own copy
* Welcome page: added the full typing guide and corrected it (ʌ/Ʌ are typed with `;`, not `q`;
  `--` gives an en dash – and `---` an em dash —)
* Help text and welcome page now call ā ē ī ō ū "vowels with macron" (not "barred vowels")
* Removed the separate Linux keyboard source; Linux uses the main keyboard
* On-screen keyboard: fixed the A and backtick key labels, added the `;` letters to
  I, U, C, V and N, and removed the Alt and Ctrl+Shift labels, which showed characters
  those keys don't type

1.2 (2019-10-01)
----------------
* Created by K. Blewett
