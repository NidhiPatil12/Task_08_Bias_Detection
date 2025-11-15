This project investigates whether Large Language Models (LLMs) exhibit bias when generating narratives from identical cricket performance data under different prompt framings. Using anonymized cricket 
statistics (Player A–Player K), four hypotheses were tested: framing bias (positive vs negative wording), identifier bias (real names vs anonymized IDs), confirmation bias (primed assumptions), and selection bias 
(metric-based emphasis).
Prompts were systematically varied while keeping the dataset constant. Responses were collected from GPT-4.1-mini (3 samples per condition) and analysed for sentiment, terminology choices, and recommendation patterns. 
Sentiment polarity scores, player-mention frequencies, and key phrases were extracted to quantify systematic variation.
Results show clear evidence of framing bias: positive prompts consistently produced higher sentiment scores and emphasized “potential,” whereas negative prompts generated lower polarity and highlighted “weaknesses” 
even for statistically identical players. Confirmation bias was also observed; when the prompt primed a specific player as “struggling,” the model justified that assumption despite neutral statistics.
Identifier bias was minimal due to anonymization, suggesting that real-name usage may be a larger risk factor. Selection bias was strongly present: strike-rate prompts favoured different players than overall-performance 
prompts, indicating that model’s over-privilege whichever metric the prompt emphasizes.
These findings indicate that LLM narratives are highly sensitive to prompt framing, subjective wording, and contextual priming even when the underlying data does not change.
Mitigation strategies such as neutral wording, structured templates, and explicit metric constraints can significantly reduce biased interpretations.

