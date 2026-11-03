# Codebook — GEQ Brazilian Portuguese adaptation data

This codebook describes the variables in the data files of the `data/` folder. All files contain one row per participant (n = 115). In every file, the first row contains generic column names (`Column3`, `Column4`, ...) exported from the online form, and the **second row contains the item wording in Portuguese**, which is used as the column header in the analysis notebook (`skiprows=1`). Participant rows start on the third row.

Files can be linked row by row through the participant identifier in the first column (`id`, 1–115).

## Response scale (all GEQ items)

GEQ items are stored as text labels that include the numeric code in parentheses. To obtain the numeric score, extract the number in parentheses.

| Stored value | Code | English anchor |
|---|---|---|
| `nada (0)` | 0 | not at all |
| `ligeiramente (1)` | 1 | slightly |
| `moderadamente (2)` | 2 | moderately |
| `bastante (3)` | 3 | fairly |
| `extremamente (4)` | 4 | extremely |

## `GEQ_Core.xlsx` — GEQ Core Module (33 items)

| Column | Variable | Item wording as administered (header) | Original item (English) | Component | Values |
|---|---|---|---|---|---|
| 1 | `id` | — | — | — | integer, 1–115 |
| 2 | `CM_Q1` | Eu me senti contente | I felt content | Positive Affect | scale 0–4 |
| 3 | `CM_Q2` | Eu me senti habilidoso | I felt skilful | Competence | scale 0–4 |
| 4 | `CM_Q3` | Fiquei interessado na história do jogo | I was interested in the game's story | Immersion | scale 0–4 |
| 5 | `CM_Q4` | Achei divertido | I thought it was fun | Positive Affect | scale 0–4 |
| 6 | `CM_Q5` | Eu estava totalmente envolvido com o jogo | I was fully occupied with the game | Flow | scale 0–4 |
| 7 | `CM_Q6` | Eu me senti feliz | I felt happy | Positive Affect | scale 0–4 |
| 8 | `CM_Q7` | Isso me deixou de mau humor | It gave me a bad mood | Negative Affect | scale 0–4 |
| 9 | `CM_Q8` | Pensei em outras coisas | I thought about other things | Negative Affect | scale 0–4 |
| 10 | `CM_Q9` | Achei ele cansativo | I found it tiresome | Negative Affect | scale 0–4 |
| 11 | `CM_Q10` | Eu me senti competente | I felt competent | Competence | scale 0–4 |
| 12 | `CM_Q11` | Achei ele difícil | I thought it was hard | Challenge | scale 0–4 |
| 13 | `CM_Q12` | Era esteticamente agradável | It was aesthetically pleasing | Immersion | scale 0–4 |
| 14 | `CM_Q13` | Esqueci de tudo ao meu redor | I forgot everything around me | Flow | scale 0–4 |
| 15 | `CM_Q14` | Eu me senti bem | I felt good | Positive Affect | scale 0–4 |
| 16 | `CM_Q15` | Fui bom nele | I was good at it | Competence | scale 0–4 |
| 17 | `CM_Q16` | Eu me senti entediado | I felt bored | Negative Affect | scale 0–4 |
| 18 | `CM_Q17` | Eu me senti bem-sucedido | I felt successful | Competence | scale 0–4 |
| 19 | `CM_Q18` | Eu me senti imaginativo | I felt imaginative | Immersion | scale 0–4 |
| 20 | `CM_Q19` | Senti que podia explorar as coisas | I felt that I could explore things | Immersion | scale 0–4 |
| 21 | `CM_Q20` | Gostei dele | I enjoyed it | Positive Affect | scale 0–4 |
| 22 | `CM_Q21` | Fui rápido em atingir os objetivos do jogo | I was fast at reaching the game's targets | Competence | scale 0–4 |
| 23 | `CM_Q22` | Eu me senti incomodado | I felt annoyed | Tension | scale 0–4 |
| 24 | `CM_Q23` | Eu me senti pressionado | I felt pressured | Challenge | scale 0–4 |
| 25 | `CM_Q24` | Eu me senti irritado | I felt irritable | Tension | scale 0–4 |
| 26 | `CM_Q25` | Perdi a noção do tempo | I lost track of time | Flow | scale 0–4 |
| 27 | `CM_Q26` | Eu me senti desafiado | I felt challenged | Challenge | scale 0–4 |
| 28 | `CM_Q27` | Achei impressionante | I found it impressive | Immersion | scale 0–4 |
| 29 | `CM_Q28` | Estava profundamente concentrado no jogo | I was deeply concentrated in the game | Flow | scale 0–4 |
| 30 | `CM_Q29` | Eu me senti frustrado | I felt frustrated | Tension | scale 0–4 |
| 31 | `CM_Q30` | Pareceu uma experiência valiosa | It felt like a rich experience | Immersion | scale 0–4 |
| 32 | `CM_Q31` | Perdi a conexão com o mundo exterior | I lost connection with the outside world | Flow | scale 0–4 |
| 33 | `CM_Q32` | Senti a pressão do tempo | I felt time pressure | Challenge | scale 0–4 |
| 34 | `CM_Q33` | Tive de me esforçar muito no jogo | I had to put a lot of effort into it | Challenge | scale 0–4 |
| 35 | `platform` | Em qual plataforma (sistema operacional) você utilizou o jogo? | Device used to play the game | — | `PC`; `Celular` (smartphone); `Tablet` |
| 36 | `doubt` | Você ficou com alguma dúvida com alguma questão deste questionário? | Comprehension check: any doubt about the questionnaire items | — | `Sim` (yes); `Não`/`Nao`/`nao` (no) |

## `PGQ_Post-Game.xlsx` — GEQ Post-Game Module (17 items)

| Column | Variable | Item wording as administered (header) | Original item (English) | Component | Values |
|---|---|---|---|---|---|
| 1 | `id` | — | — | — | integer, 1–115 |
| 2 | `PGQ_Q1` | Eu me senti revigorado | I felt revived | Positive Experience | scale 0–4 |
| 3 | `PGQ_Q2` | Eu me senti mal | I felt bad | Negative Experience | scale 0–4 |
| 4 | `PGQ_Q3` | Achei difícil voltar à realidade | I found it hard to get back to reality | Returning to Reality | scale 0–4 |
| 5 | `PGQ_Q4` | Eu me senti culpado | I felt guilty | Negative Experience | scale 0–4 |
| 6 | `PGQ_Q5` | Foi como uma vitória | It felt like a victory | Positive Experience | scale 0–4 |
| 7 | `PGQ_Q6` | Achei uma perda de tempo | I found it a waste of time | Negative Experience | scale 0–4 |
| 8 | `PGQ_Q7` | Eu me senti energizado | I felt energised | Positive Experience | scale 0–4 |
| 9 | `PGQ_Q8` | Eu me senti satisfeito | I felt satisfied | Positive Experience | scale 0–4 |
| 10 | `PGQ_Q9` | Eu me senti desorientado | I felt disoriented | Returning to Reality | scale 0–4 |
| 11 | `PGQ_Q10` | Eu me senti exausto | I felt exhausted | Tiredness | scale 0–4 |
| 12 | `PGQ_Q11` | Senti que poderia ter feito coisas mais úteis | I felt that I could have done more useful things | Negative Experience | scale 0–4 |
| 13 | `PGQ_Q12` | Eu me senti poderoso | I felt powerful | Positive Experience | scale 0–4 |
| 14 | `PGQ_Q13` | Eu me senti esgotado | I felt weary | Tiredness | scale 0–4 |
| 15 | `PGQ_Q14` | Senti remorso | I felt regret | Negative Experience | scale 0–4 |
| 16 | `PGQ_Q15` | Eu me senti envergonhado | I felt ashamed | Negative Experience | scale 0–4 |
| 17 | `PGQ_Q16` | Eu me senti orgulhoso | I felt proud | Positive Experience | scale 0–4 |
| 18 | `PGQ_Q17` | Tive a sensação de ter voltado de uma viagem | I had a sense that I had returned from a journey | Returning to Reality | scale 0–4 |
| 19 | `doubt` | Você ficou com alguma dúvida com alguma questão deste questionário? | Comprehension check: any doubt about the questionnaire items | — | `Sim` (yes); `Não`/`Nao`/`nao` (no) |

## `SPGQ_Social_Presence.xlsx` — GEQ Social Presence Module (17 items)

| Column | Variable | Item wording as administered (header) | Original item (English) | Component | Values |
|---|---|---|---|---|---|
| 1 | `id` | — | — | — | integer, 1–115 |
| 2 | `SPGQ_Q1` | Tive empatia com o(s) outro(s) | I empathized with the other(s) | Empathy | scale 0–4 |
| 3 | `SPGQ_Q2` | As minhas ações dependiam das ações do(s) outro(s) | My actions depended on the other(s) actions | Behavioural Involvement | scale 0–4 |
| 4 | `SPGQ_Q3` | As ações dos outros dependiam das minhas ações | The other's actions were dependent on my actions | Behavioural Involvement | scale 0–4 |
| 5 | `SPGQ_Q4` | Eu me senti conectado com o(s) outro(s) | I felt connected to the other(s) | Empathy | scale 0–4 |
| 6 | `SPGQ_Q5` | Os outros prestaram atenção em mim | The other(s) paid close attention to me | Behavioural Involvement | scale 0–4 |
| 7 | `SPGQ_Q6` | Prestei muita atenção no(s) outro(s) | I paid close attention to the other(s) | Behavioural Involvement | scale 0–4 |
| 8 | `SPGQ_Q7` | Senti ciúmes do(s) outro(s) | I felt jealous about the other(s) | Negative Feelings | scale 0–4 |
| 9 | `SPGQ_Q8` | Achei que foi agradável estar com o(s) outro(s) | I found it enjoyable to be with the other(s) | Empathy | scale 0–4 |
| 10 | `SPGQ_Q9` | Quando eu estava feliz, o(s) outro(s) também estava(m) feliz(es) | When I was happy, the other(s) was(were) happy | Empathy | scale 0–4 |
| 11 | `SPGQ_Q10` | Quando o(s) outro(s) estava(m) feliz(es), eu também estava feliz | When the other(s) was(were) happy, I was happy | Empathy | scale 0–4 |
| 12 | `SPGQ_Q11` | Influenciei o humor do(s) outro(s) | I influenced the mood of the other(s) | Negative Feelings | scale 0–4 |
| 13 | `SPGQ_Q12` | Fui influenciado pelo humor do(s) outro(s) | I was influenced by the other(s) moods | Negative Feelings | scale 0–4 |
| 14 | `SPGQ_Q13` | Admirei o(s) outro(s) | I admired the other(s) | Empathy | scale 0–4 |
| 15 | `SPGQ_Q14` | O que o(s) outro(s) fazia(m) afetava o que eu fazia | What the other(s) did affected what I did | Behavioural Involvement | scale 0–4 |
| 16 | `SPGQ_Q15` | O que eu fazia afetava o que o(s) outro(s) fazia(m) | What I did affected what the other(s) did | Behavioural Involvement | scale 0–4 |
| 17 | `SPGQ_Q16` | Eu me senti vingativo | I felt revengeful | Negative Feelings | scale 0–4 |
| 18 | `SPGQ_Q17` | Senti tristeza (see note) | I felt schadenfreude (malicious delight) | Negative Feelings | scale 0–4 |
| 19 | `doubt` | Você ficou com alguma dúvida com alguma questão deste questionário? | Comprehension check: any doubt about the questionnaire items | — | `Sim` (yes); `Não`/`Nao`/`nao` (no) |

**Note on `SPGQ_Q17`.** The original item is "I felt schadenfreude (malicious delight)". In this dataset it was administered as "Senti tristeza" ("I felt sad"), which does not preserve the original meaning (see the article, Section 3.2). The recommended wording for future use is "Senti prazer com o fracasso do(s) outro(s)".

## `population_info.xlsx` — participant profile

| Column | Variable | Question as administered (header) | Description | Values (stored text → English) |
|---|---|---|---|---|
| 1 | `id` | — | Participant identifier | integer, 1–115 |
| 2 | `age_group` | Idade | Age group | `18-24 anos`; `25-34 anos`; `35-44 anos` |
| 3 | `gender` | Gênero | Self-reported gender | `Masculino` (male); `Feminino` (female); `Prefiro não informar` (prefer not to say) |
| 4 | `education` | Nível de Escolaridade | Highest level of education completed | `Ensino Fundamental Completo` (primary complete); `Ensino Médio Completo` (secondary complete); `Ensino Superior Incompleto` (higher education incomplete); `Ensino Superior Completo` (higher education complete); `Pós-graduação` (postgraduate) |
| 5 | `gaming_freq` | Usa jogos de plataforma com que frequência | Current gaming frequency | `Frequente (todos os dias)` (every day); `Regularmente (algumas vezes por semana)` (a few times a week); `Ocasionalmente (algumas vezes por mês)` (a few times a month); `Raramente (algumas vezes por ano)` (a few times a year); `Nunca` (never) |
| 6 | `device` | Quais dispositivos mais gosta de jogar | Preferred gaming device | `PC`; `Smartphone`; `Playstation`; `Xbox`; `Swich` (Nintendo Switch, typo in source); `Tablet`; `Outros` (other) |
| 7 | `favorite_mechanic` | Qual mecânica de jogo favorito | Favorite game mechanic (free choice among options) | e.g., `Toque preciso e movimento`; `Toque preciso e timing`; `Toque preciso na tela`; `Toque preciso e rítmico`; `Movimento e dança` |

## Other files

- `GEQ_Final_Translation_all_modules.xlsx`: final Brazilian Portuguese version of the three modules, with the original English item next to each translated item.
- `GEQ_translation_complete_analysis.ipynb` (repository root): Python notebook with all analyses (reliability, KMO, Bartlett's test, EFA with principal components extraction and Promax rotation).

## Notes for reuse

- Text values have minor spelling variations in some columns (e.g., `Não`/`Nao`/`nao`); normalize them before analysis.
- Variable names in the `Variable` column (e.g., `CM_Q1`) are suggested names for reuse; the files themselves use the Portuguese item wording as header.
- Component assignment follows the original GEQ scoring guidelines (Poels, de Kort & IJsselsteijn, 2007).
