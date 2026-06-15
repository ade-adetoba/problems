curl -L -X POST \ \
  -H "Accept: application/vnd.github+json" \ \
  -H "Authorization: Bearer $GITHUB_TOKEN" \ \
  -H "X-GitHub-Api-Version: 2022-11-28" \ \
  -H "Content-Type: application/json" \ \
  https://models.github.ai/inference/chat/completions \ \
  -d '{"model":"openai/gpt-4o","messages":[{"role":"user","content":"say hi"}]}'




(venv) adetoa3@MAC-AA-D2X19XK5CC test3 % curl -L -X POST \
-H "Accept: application/vnd.github+json" \
-H "Authorization: Bearer $GITHUB_TOKEN" \
-H "X-GitHub-Api-Version: 2022-11-28" \
-H "Content-Type: application/json" \
https://models.github.ai/inference/chat/completions \
-d '{"model":"openai/gpt-4o","messages":[{"role":"user","content":"say hi"}]}'
{"choices":[{"content_filter_results":{"hate":{"filtered":false,"severity":"safe"},"protected_material_code":{"detected":false,"filtered":false},"protected_material_text":{"detected":false,"filtered":false},"self_harm":{"filtered":false,"severity":"safe"},"sexual":{"filtered":false,"severity":"safe"},"violence":{"filtered":false,"severity":"safe"}},"finish_reason":"stop","index":0,"logprobs":null,"message":{"annotations":[],"content":"Hello! How can I assist you today? 😊","refusal":null,"role":"assistant"}}],"created":1781508050,"id":"chatcmpl-DqvukhIP8rzBpx2MbsltCHs7uxgyp","model":"gpt-4o-2024-11-20","object":"chat.completion","prompt_filter_results":[{"prompt_index":0,"content_filter_results":{"hate":{"filtered":false,"severity":"safe"},"jailbreak":{"detected":false,"filtered":false},"self_harm":{"filtered":false,"severity":"safe"},"sexual":{"filtered":false,"severity":"safe"},"violence":{"filtered":false,"severity":"safe"}}}],"service_tier":"default","system_fingerprint":"fp_49e2bef596","usage":{"completion_tokens":11,"completion_tokens_details":{"accepted_prediction_tokens":0,"audio_tokens":0,"reasoning_tokens":0,"rejected_prediction_tokens":0},"latency_checkpoint":{"engine_tbt_ms":6,"engine_ttft_ms":32,"engine_ttlt_ms":99,"pre_inference_ms":96,"service_tbt_ms":7,"service_ttft_ms":509,"service_ttlt_ms":568,"total_duration_ms":482,"user_visible_ttft_ms":412},"prompt_tokens":9,"prompt_tokens_details":{"audio_tokens":0,"cached_tokens":0},"total_tokens":20}}
(venv) adetoa3@MAC-AA-D2X19XK5CC test3 % curl -L -X POST \
-H "Accept: application/vnd.github+json" \
-H "Authorization: Bearer $GITHUB_TOKEN" \
-H "X-GitHub-Api-Version: 2022-11-28" \
-H "Content-Type: application/json" \
https://models.github.ai/inference/chat/completions \
-d '{"model":"openai/gpt-4o","messages":[{"role":"user","content":"say hi"}]}'
{"choices":[{"content_filter_results":{"hate":{"filtered":false,"severity":"safe"},"protected_material_code":{"detected":false,"filtered":false},"protected_material_text":{"detected":false,"filtered":false},"self_harm":{"filtered":false,"severity":"safe"},"sexual":{"filtered":false,"severity":"safe"},"violence":{"filtered":false,"severity":"safe"}},"finish_reason":"stop","index":0,"logprobs":null,"message":{"annotations":[],"content":"Hello! How can I assist you today? 😊","refusal":null,"role":"assistant"}}],"created":1781508059,"id":"chatcmpl-Dqvut3WjdtrEzmDkYZC8BW05y7bhT","model":"gpt-4o-2024-11-20","object":"chat.completion","prompt_filter_results":[{"prompt_index":0,"content_filter_results":{"hate":{"filtered":false,"severity":"safe"},"jailbreak":{"detected":false,"filtered":false},"self_harm":{"filtered":false,"severity":"safe"},"sexual":{"filtered":false,"severity":"safe"},"violence":{"filtered":false,"severity":"safe"}}}],"service_tier":"default","system_fingerprint":"fp_49e2bef596","usage":{"completion_tokens":11,"completion_tokens_details":{"accepted_prediction_tokens":0,"audio_tokens":0,"reasoning_tokens":0,"rejected_prediction_tokens":0},"latency_checkpoint":{"engine_tbt_ms":6,"engine_ttft_ms":27,"engine_ttlt_ms":93,"pre_inference_ms":91,"service_tbt_ms":7,"service_ttft_ms":480,"service_ttlt_ms":541,"total_duration_ms":461,"user_visible_ttft_ms":389},"prompt_tokens":9,"prompt_tokens_details":{"audio_tokens":0,"cached_tokens":0},"total_tokens":20}}
(venv) adetoa3@MAC-AA-D2X19XK5CC test3 % 
