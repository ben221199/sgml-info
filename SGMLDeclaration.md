# SGML Declaration

| Path | Section | Production | Value |
| - | - | - | - |
| `SGML` | 13 | [171] SGML declaration | `"ISO 8879-1986"`
| `SGML`.`CHARSET` | 13.1<br>13.1.1 | [172] document character set<br>[173] character set description | *See children* |
| `SGML`.`CHARSET`.`BASESET` | 13.1.1.1 | [174] base character set | [`public identifier`](#) |
| `SGML`.`CHARSET`.`DESCSET` | 13.1.1.2 | [175] described character set portion |
| `SGML`.`CAPACITY` | 13.2 | [180] capacity set |
| `SGML`.`SCOPE` | 13.3 | [181] concrete syntax scope | `DOCUMENT` or `INSTANCE` |
| `SGML`.`SYNTAX` | 13.4 | [182] concrete syntax |
| `SGML`.`FEATURES` | 13.5 | [195] feature use | *See children* |
| `SGML`.`FEATURES`.`MINIMIZE` | 13.5.1 | [196] markup minimization features | *See children* |
| `SGML`.`FEATURES`.`MINIMIZE`.`DATATAG` | ^ | ^ | `NO` or `YES` |
| `SGML`.`FEATURES`.`MINIMIZE`.`OMITTAG` | ^ | ^ | `NO` or `YES` |
| `SGML`.`FEATURES`.`MINIMIZE`.`RANK` | ^ | ^ | `NO` or `YES` |
| `SGML`.`FEATURES`.`MINIMIZE`.`SHORTTAG` | ^ | ^ | `NO` or `YES` |
| `SGML`.`FEATURES`.`LINK` | 13.5.2 | [197] link type features | *See children* |
| `SGML`.`FEATURES`.`LINK`.`SIMPLE` | ^ | ^ | `NO` or `YES` |
| `SGML`.`FEATURES`.`LINK`.`IMPLICIT` | ^ | ^ | `NO` or `YES` |
| `SGML`.`FEATURES`.`LINK`.`EXPLICIT` | ^ | ^ | `NO` or (`YES`, [`ps+`](#), [`number`](#))  |
| `SGML`.`APPINFO` | 13.6 | [199] application-specific information | `NONE` or [`minimum literal`](#) |
