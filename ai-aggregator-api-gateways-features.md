# AI Aggregator API Gateways: Features Comparison (December 2025)

This document provides a detailed feature-by-feature comparison of AI aggregator API gateways, helping you choose the right solution based on specific capabilities. The comparison covers model access, routing features, observability, security, pricing models, and specialized capabilities.

---

## 1. Model Access & Provider Support

| **Gateway** | **Total Models** | **OpenAI** | **Anthropic** | **Google** | **xAI** | **Meta Llama** | **Open-Source** | **Self-Hosted/Local** |
|-------------|------------------|------------|---------------|------------|---------|----------------|-----------------|----------------------|
| **OpenRouter** | 500+ | ✅ GPT-5, o3 | ✅ Claude Opus 4.5 | ✅ Gemini 3 | ✅ Grok 4 | ✅ Llama 4 | ✅ DeepSeek, Mistral | ❌ |
| **LiteLLM** | 100+ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ Ollama |
| **Portkey** | 1,600+ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Helicone** | 100+ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Cloudflare AI Gateway** | 20+ providers | ✅ | ✅ | ✅ | ✅ DeepSeek | ❌ | ✅ Workers AI | ❌ |
| **Vercel AI Gateway** | Hundreds | ✅ GPT-5 | ✅ Sonnet 4 | ✅ | ✅ Grok | ✅ | ✅ | ❌ |
| **Kong AI Gateway** | 60+ features | ✅ | ✅ | ✅ GCP Gemini | ❌ | ✅ | ✅ | ✅ |
| **Amazon Bedrock** | 11,000+ | ✅ via Foundry | ✅ Claude | ❌ | ❌ | ✅ | ✅ | ❌ |
| **Together AI** | 200+ | ❌ | ❌ | ❌ | ❌ | ✅ Llama 4 | ✅ Full focus | ❌ |
| **Groq** | Multiple | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ |
| **Martian** | Dozens | ✅ | ✅ | ❌ | ❌ | ✅ | ✅ Mistral | ❌ |
| **DeepInfra** | 100+ | ❌ | ✅ Claude | ❌ | ❌ | ✅ Llama 4 | ✅ | ❌ |
| **Fireworks AI** | Multiple | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ |
| **Eden AI** | 100+ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ❌ |
| **Novita AI** | 200+ | ✅ GPT OSS | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ |

**Key Insights**:
- **OpenRouter** offers the largest model catalog with 500+ models from 60+ providers
- **Portkey** supports the most LLM connections at 1,600+
- **Amazon Bedrock** provides access to 11,000+ models through AI Foundry
- **LiteLLM**, **Kong**, and **Helicone** support self-hosted/local models via Ollama

---

## 2. API Compatibility & Integration

| **Gateway** | **OpenAI-Compatible API** | **SDK Support** | **BYOK (Bring Your Own Key)** | **MCP Support** | **Webhook/Streaming** |
|-------------|---------------------------|-----------------|-------------------------------|-----------------|----------------------|
| **OpenRouter** | ✅ Drop-in replacement | REST API | ❌ | ❌ | ✅ Streaming |
| **LiteLLM** | ✅ Full compatibility | Python SDK | ✅ | ❌ | ✅ |
| **Portkey** | ✅ | Python, Node.js | ✅ Virtual keys | ✅ | ✅ |
| **Helicone** | ✅ | Multiple SDKs | ✅ | ❌ | ✅ |
| **Cloudflare AI Gateway** | ✅ Unified API | REST, Workers | ✅ Store in vault | ❌ | ✅ |
| **Vercel AI Gateway** | ✅ | AI SDK 5, OpenAI SDK | ✅ 0% markup | ❌ | ✅ |
| **Kong AI Gateway** | ✅ Universal LLM API | Lua, Go, JS plugins | ✅ | ✅ MCP governance | ✅ |
| **Amazon Bedrock** | Partial | AWS SDKs | N/A (AWS native) | ✅ AgentCore | ✅ |
| **Together AI** | ✅ | REST API | N/A | ❌ | ✅ |
| **Groq** | ✅ | REST API | N/A | ❌ | ✅ |
| **Martian** | ✅ Drop-in replacement | REST API | ✅ | ❌ | ✅ |
| **DeepInfra** | ✅ | REST API | N/A | ❌ | ✅ |
| **Fireworks AI** | ✅ | REST API | N/A | ❌ | ✅ |
| **Eden AI** | ✅ | REST API, Plugins | ✅ BYOA | ❌ | ✅ |
| **Novita AI** | ✅ | REST API | N/A | ❌ | ✅ |

**Key Insights**:
- All gateways support OpenAI-compatible API format for easy migration
- **Kong AI Gateway** leads in MCP (Model Context Protocol) support with full governance
- **Vercel AI Gateway** offers seamless AI SDK 5 integration with 0% BYOK markup
- **Portkey** provides virtual keys for secure credential management

---

## 3. Routing & Load Balancing

| **Gateway** | **Automatic Failover** | **Load Balancing** | **Dynamic Routing** | **A/B Testing** | **Semantic Routing** | **Cost-Based Routing** |
|-------------|------------------------|-------------------|---------------------|-----------------|---------------------|----------------------|
| **OpenRouter** | ✅ | Basic | ❌ | ❌ | ❌ | ❌ |
| **LiteLLM** | ✅ Fallback logic | ✅ | ✅ | ❌ | ❌ | ❌ |
| **Portkey** | ✅ | ✅ Configurable | ✅ Rules-based | ❌ | ❌ | ❌ |
| **Helicone** | ✅ Circuit breaking | ✅ Health-aware | ❌ | ❌ | ❌ | ❌ |
| **Cloudflare AI Gateway** | ✅ | ✅ | ✅ Visual interface | ✅ | ❌ | ❌ |
| **Vercel AI Gateway** | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ |
| **Kong AI Gateway** | ✅ Retries | ✅ Multiple algorithms | ✅ | ❌ | ✅ Semantic matching | ❌ |
| **Amazon Bedrock** | ✅ | ✅ | ✅ Prompt routing | ❌ | ❌ | ✅ ~30% savings |
| **Together AI** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Groq** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Martian** | ✅ Automatic | ❌ | ✅ Per-query | ❌ | ❌ | ✅ 20-96% savings |
| **DeepInfra** | ❌ | ✅ Auto-scaling | ❌ | ❌ | ❌ | ❌ |
| **Fireworks AI** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Eden AI** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Novita AI** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |

**Key Insights**:
- **Kong AI Gateway** offers the most advanced routing with semantic matching and multiple algorithms
- **Martian** specializes in cost-based dynamic routing with claimed 20-96% savings
- **Amazon Bedrock** provides automatic prompt routing for ~30% cost savings
- **Cloudflare AI Gateway** enables A/B testing through a visual interface

---

## 4. Observability & Analytics

| **Gateway** | **Cost Tracking** | **Latency Metrics** | **Token Usage** | **Error Monitoring** | **Custom Dashboards** | **Log Export** |
|-------------|-------------------|--------------------|-----------------|--------------------|----------------------|----------------|
| **OpenRouter** | ✅ Per-model | Basic | ✅ | Basic | ❌ | ❌ |
| **LiteLLM** | ✅ Full attribution | ✅ | ✅ | ✅ | ✅ Postgres | ✅ Multiple integrations |
| **Portkey** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ Audit logs |
| **Helicone** | ✅ Real-time | ✅ 8ms P50 | ✅ | ✅ | ✅ | ✅ |
| **Cloudflare AI Gateway** | ✅ Custom costs | ✅ | ✅ | ✅ | ✅ | ✅ Logpush |
| **Vercel AI Gateway** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Kong AI Gateway** | ✅ LLM cost control | ✅ | ✅ | ✅ | ✅ Metrics export | ✅ OpenTelemetry |
| **Amazon Bedrock** | ✅ | ✅ | ✅ | ✅ | ✅ CloudWatch | ✅ |
| **Together AI** | ✅ | ✅ | ✅ | Basic | ❌ | ❌ |
| **Groq** | ✅ | ✅ | ✅ | Basic | ❌ | ❌ |
| **Martian** | ✅ Cost calculator | Basic | ✅ | Basic | ❌ | ❌ |
| **DeepInfra** | ✅ Spending limits | ✅ | ✅ | Basic | ❌ | ❌ |
| **Fireworks AI** | ✅ | ✅ | ✅ | Basic | ❌ | ❌ |
| **Eden AI** | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| **Novita AI** | ✅ | ✅ | ✅ | Basic | ❌ | ❌ |

**Key Insights**:
- **Helicone** is built specifically for observability with Rust-based performance
- **LiteLLM** integrates with multiple observability platforms (Lunary, MLflow, Langfuse, etc.)
- **Kong AI Gateway** supports OpenTelemetry for distributed tracing
- **Cloudflare AI Gateway** allows custom cost configuration for negotiated rates

---

## 5. Security & Compliance

| **Gateway** | **SOC 2** | **GDPR** | **HIPAA** | **ISO 27001** | **Data Retention Control** | **VPC/On-Prem** |
|-------------|-----------|----------|-----------|---------------|---------------------------|-----------------|
| **OpenRouter** | ❌ | ✅ Privacy filters | ❌ | ❌ | ❌ | ❌ |
| **LiteLLM** | Enterprise | ✅ | Enterprise | ❌ | ✅ Self-hosted | ✅ Full control |
| **Portkey** | ✅ Type 2 | ✅ | ✅ | ✅ | ✅ ZDR available | ✅ Private cloud |
| **Helicone** | ✅ | ✅ | ❌ | ❌ | ✅ | ✅ VPC |
| **Cloudflare AI Gateway** | ✅ | ✅ | ❌ | ❌ | ✅ Logpush | ❌ |
| **Vercel AI Gateway** | ✅ | ✅ | ❌ | ❌ | ✅ | ❌ |
| **Kong AI Gateway** | Enterprise | ✅ | Enterprise | Enterprise | ✅ Self-hosted | ✅ Full control |
| **Amazon Bedrock** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ AWS VPC |
| **Together AI** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Groq** | ❌ | ✅ | ❌ | ❌ | ❌ | ✅ Private cloud |
| **Martian** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| **DeepInfra** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Fireworks AI** | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ |
| **Eden AI** | ❌ | ✅ | ❌ | ❌ | ❌ | Enterprise |
| **Novita AI** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |

**Key Insights**:
- **Portkey** offers the most comprehensive compliance: SOC 2 Type 2, GDPR, HIPAA, and ISO 27001
- **Amazon Bedrock** provides full AWS-grade security and compliance
- **LiteLLM** and **Kong** offer complete control through self-hosting
- **Fireworks AI** is one of few inference providers with SOC2 and HIPAA compliance

---

## 6. Caching & Performance Optimization

| **Gateway** | **Response Caching** | **Semantic Caching** | **Edge Deployment** | **Latency Overhead** | **Rate Limiting** |
|-------------|---------------------|---------------------|--------------------|--------------------|-------------------|
| **OpenRouter** | ❌ | ❌ | ❌ | Variable | Provider-based |
| **LiteLLM** | ✅ | ❌ | ❌ | 8ms P95 | ✅ Configurable |
| **Portkey** | ✅ | ❌ | ✅ Edge workers | 20-40ms | ✅ |
| **Helicone** | ✅ | ❌ | ✅ | 8ms P50 | ✅ |
| **Cloudflare AI Gateway** | ✅ 90% latency reduction | ❌ | ✅ Global edge | Minimal | ✅ Flexible |
| **Vercel AI Gateway** | ❌ | ❌ | ✅ Edge | Sub-20ms | ❌ (no limits) |
| **Kong AI Gateway** | ✅ | ✅ Semantic | ✅ | Minimal | ✅ |
| **Amazon Bedrock** | ❌ | ❌ | ✅ AWS regions | Variable | ✅ |
| **Together AI** | ❌ | ❌ | ❌ | Sub-100ms | API-based |
| **Groq** | ❌ | ❌ | ❌ | Ultra-low | Tier-based |
| **Martian** | ❌ | ❌ | ❌ | Variable | API-based |
| **DeepInfra** | ❌ | ❌ | ❌ | Low | 200 concurrent |
| **Fireworks AI** | ❌ | ❌ | ❌ | Ultra-low | API-based |
| **Eden AI** | ✅ Personal+ | ❌ | ❌ | Variable | Plan-based |
| **Novita AI** | ❌ | ❌ | ❌ | Low | API-based |

**Key Insights**:
- **Cloudflare AI Gateway** offers the best caching with up to 90% latency reduction
- **Kong AI Gateway** uniquely offers semantic caching
- **Groq** and **Fireworks AI** focus on ultra-low latency inference
- **Vercel AI Gateway** imposes no rate limits from their side

---

## 7. Pricing Models & Free Tiers

| **Gateway** | **Pricing Model** | **Markup** | **Free Tier** | **Entry Price** | **Enterprise** |
|-------------|-------------------|------------|---------------|-----------------|----------------|
| **OpenRouter** | Pay-as-you-go | 0% + 5.5% credit fee | ❌ | Credit purchase | ✅ Volume discounts |
| **LiteLLM** | Self-host or Enterprise | 0% (self-host) | ✅ Self-host | Free | ✅ SSO, audit logs |
| **Portkey** | Usage-based | Varies | ✅ 10K req/mo | $49/month | ✅ Custom |
| **Helicone** | Usage-based | 0% | ✅ 10K req/mo | Team pricing | ✅ Custom |
| **Cloudflare AI Gateway** | Usage-based | 0% + transaction fee | ✅ Free base | Per-log charges | ✅ |
| **Vercel AI Gateway** | Pay-as-you-go | 0% | ✅ $5/month | Credit-based | ✅ |
| **Kong AI Gateway** | Self-host or Enterprise | 0% (self-host) | ✅ Self-host | Free | ✅ Kong Inc. |
| **Amazon Bedrock** | Pay-per-token | 0% | ✅ $200 credits | Token-based | ✅ Provisioned |
| **Together AI** | Pay-per-token | N/A | ❌ | Token-based | ✅ Dedicated |
| **Groq** | Pay-per-token | N/A | ✅ Free tier | $0.11/M input | ✅ Dedicated |
| **Martian** | Usage-based | Savings model | ❌ | Contact | ✅ |
| **DeepInfra** | Pay-per-token | N/A | ❌ | $0.03/M input | ❌ |
| **Fireworks AI** | Pay-per-token | N/A | ✅ $1 credits | Token-based | ✅ |
| **Eden AI** | Pay-per-call | 0% | ✅ $10 credits | $29/month | ✅ Custom |
| **Novita AI** | Pay-as-you-go | N/A | Promotions | $0.05/M input | ❌ |

**Key Insights**:
- **OpenRouter**, **Helicone**, **Cloudflare**, and **Vercel** charge zero markup on model pricing
- **LiteLLM** and **Kong** are completely free when self-hosted
- **Vercel AI Gateway** provides the most generous recurring free tier at $5/month
- **Amazon Bedrock** offers $200 in free credits for new AWS customers

---

## 8. Specialized Capabilities

| **Gateway** | **Guardrails** | **Prompt Templates** | **RAG Integration** | **Fine-Tuning** | **Multi-Modal** | **Batch Processing** |
|-------------|----------------|---------------------|--------------------|-----------------|-----------------|--------------------|
| **OpenRouter** | ✅ Privacy filters | ❌ | ❌ | ❌ | ✅ Audio, PDF | ❌ |
| **LiteLLM** | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| **Portkey** | ✅ 50+ guardrails | ✅ | ❌ | ❌ | ✅ | ❌ |
| **Helicone** | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| **Cloudflare AI Gateway** | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| **Vercel AI Gateway** | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| **Kong AI Gateway** | ✅ Content safety | ✅ | ✅ Automated | ❌ | ✅ | ❌ |
| **Amazon Bedrock** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 50% discount |
| **Together AI** | ❌ | ❌ | ❌ | ✅ Pay-per-token | ✅ | ❌ |
| **Groq** | ❌ | ❌ | ❌ | ❌ | ✅ STT, TTS | ✅ 25% discount |
| **Martian** | ✅ Compliance | ❌ | ❌ | ❌ | ❌ | ❌ |
| **DeepInfra** | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| **Fireworks AI** | ❌ | ❌ | ❌ | ✅ Free deploy | ✅ Image, audio | ✅ 50% discount |
| **Eden AI** | ❌ | ✅ Workflows | ✅ Chatbot builder | ❌ | ✅ Full stack | ❌ |
| **Novita AI** | ❌ | ❌ | ❌ | ✅ | ✅ Image, video | ✅ 50% discount |

**Key Insights**:
- **Portkey** offers 50+ AI guardrails for enterprise content safety
- **Kong AI Gateway** provides automated RAG pipelines to reduce hallucinations
- **Amazon Bedrock** and **Fireworks AI** offer batch processing with significant discounts
- **Eden AI** goes beyond LLMs with full multi-modal AI stack (image, audio, video, NLP)

---

## 9. Open-Source & Licensing

| **Gateway** | **Open Source** | **License** | **GitHub Stars** | **Self-Host** | **Commercial Use** |
|-------------|-----------------|-------------|------------------|---------------|-------------------|
| **OpenRouter** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **LiteLLM** | ✅ | MIT | High | ✅ | ✅ |
| **Portkey** | Partial | Apache 2.0 (gateway) | 10K+ | ✅ | ✅ |
| **Helicone** | ✅ | Open source | Growing | ✅ | ✅ |
| **Cloudflare AI Gateway** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **Vercel AI Gateway** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **Kong AI Gateway** | ✅ | Apache 2.0 | 40K+ (Kong) | ✅ | ✅ |
| **Amazon Bedrock** | ❌ | AWS | N/A | ❌ | ✅ |
| **Together AI** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **Groq** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **Martian** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **DeepInfra** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **Fireworks AI** | ❌ | Proprietary | N/A | ❌ | ✅ |
| **Eden AI** | ❌ | Proprietary | N/A | Enterprise | ✅ |
| **Novita AI** | ❌ | Proprietary | N/A | ❌ | ✅ |

**Key Insights**:
- **LiteLLM** (MIT) and **Kong** (Apache 2.0) offer the most permissive open-source licenses
- **Portkey**'s gateway is open-source (10K+ stars) while the full platform is commercial
- **Kong** has the largest open-source community with 40K+ GitHub stars

---

## 10. Quick Feature Summary by Use Case

### For Startups & Individual Developers
| Priority | Recommended Gateway | Why |
|----------|-------------------|-----|
| **Lowest cost** | LiteLLM (self-hosted) | Free, full control |
| **Easiest setup** | OpenRouter | Largest catalog, simple API |
| **Best free tier** | Vercel AI Gateway | $5 monthly credits, no markup |
| **Fastest inference** | Groq | Free tier, ultra-low latency |

### For Enterprise & Teams
| Priority | Recommended Gateway | Why |
|----------|-------------------|-----|
| **Governance & compliance** | Portkey | SOC 2, ISO 27001, HIPAA |
| **AWS integration** | Amazon Bedrock | Native AWS, 11K+ models |
| **Self-hosted control** | LiteLLM or Kong | MIT/Apache 2.0 licenses |
| **Observability focus** | Helicone | Zero markup, Rust performance |

### For Specific Workloads
| Workload | Recommended Gateway | Why |
|----------|-------------------|-----|
| **Multi-modal apps** | Eden AI | Full AI stack beyond LLMs |
| **Open-source models** | Together AI | 200+ models, best price-performance |
| **Real-time/low latency** | Groq | LPU hardware, 1,200 tokens/sec |
| **Cost optimization** | Martian | Dynamic routing, 20-96% savings |
| **Batch processing** | Amazon Bedrock or Fireworks | 50% discount on batch |

---

## 11. Integration Ecosystem

| **Gateway** | **IDE Plugins** | **CI/CD** | **Zapier/Make** | **Slack** | **Jira** | **GitHub** |
|-------------|-----------------|-----------|-----------------|-----------|----------|------------|
| **OpenRouter** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **LiteLLM** | ❌ | ✅ | ❌ | ✅ | ❌ | ❌ |
| **Portkey** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Helicone** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Cloudflare AI Gateway** | ❌ | ✅ Workers | ❌ | ❌ | ❌ | ❌ |
| **Vercel AI Gateway** | ❌ | ✅ | ❌ | ❌ | ❌ | ✅ |
| **Kong AI Gateway** | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| **Amazon Bedrock** | ✅ AWS Toolkit | ✅ | ❌ | ✅ 1-click | ✅ 1-click | ❌ |
| **Together AI** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Groq** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Martian** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **DeepInfra** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Fireworks AI** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **Eden AI** | ❌ | ❌ | ✅ Zapier, Make | ❌ | ❌ | ❌ |
| **Novita AI** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |

**Key Insights**:
- **Amazon Bedrock** offers the richest integration ecosystem with 1-click connections
- **Eden AI** provides no-code integrations via Zapier and Make
- Most gateways focus on API-first approach with CI/CD compatibility

---

## 12. Decision Matrix

Use this matrix to quickly identify the best gateway for your needs:

| **If you need...** | **Choose...** |
|--------------------|---------------|
| Largest model selection | OpenRouter (500+ models) |
| Complete open-source control | LiteLLM (MIT license) |
| Enterprise governance | Portkey (SOC 2/ISO 27001) |
| Best observability | Helicone (built-in, zero markup) |
| Cloudflare integration | Cloudflare AI Gateway |
| Vercel/AI SDK users | Vercel AI Gateway |
| Plugin extensibility | Kong AI Gateway (Apache 2.0) |
| AWS ecosystem | Amazon Bedrock |
| Open-source model focus | Together AI (200+ models) |
| Fastest inference | Groq (LPU, 1,200 tok/sec) |
| Dynamic cost optimization | Martian (20-96% savings) |
| Simple open-source access | DeepInfra (100+ models) |
| High-performance inference | Fireworks AI (SOC2/HIPAA) |
| Multi-modal beyond LLMs | Eden AI (image/audio/video) |
| Budget-friendly startup | Novita AI (GPT OSS) |

---

## References

- [OpenRouter Documentation](https://openrouter.ai/)
- [LiteLLM GitHub](https://github.com/BerriAI/litellm)
- [Portkey AI Gateway](https://portkey.ai/features/ai-gateway)
- [Helicone AI Gateway Guide](https://www.helicone.ai/blog/how-to-gateway)
- [Cloudflare AI Gateway Docs](https://developers.cloudflare.com/ai-gateway/)
- [Vercel AI Gateway Docs](https://vercel.com/docs/ai-gateway)
- [Kong AI Gateway](https://developer.konghq.com/ai-gateway/)
- [Amazon Bedrock](https://aws.amazon.com/bedrock/)
- [Together AI Products](https://www.together.ai/products)
- [Groq Cloud](https://groq.com/groqcloud)
- [Martian Model Router](https://route.withmartian.com/products/model-router)
- [DeepInfra Pricing](https://deepinfra.com/pricing)
- [Fireworks AI](https://fireworks.ai/)
- [Eden AI Platform](https://www.edenai.co/)
- [Novita AI](https://novita.ai/)
