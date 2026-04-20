# AI Observability with OpenTelemetry

The OpenTelemetry project has defined [Semantic conventions for generative AI systems](https://opentelemetry.io/docs/specs/semconv/gen-ai/) that include conventions for the signals from:
* Model spans
* Agent spans
* Generative AI input and output metrics and events

# Observability

Dynatrace had native OpenTelemetry support in the form of OTLP API and with the [Dynatrace AI Observability](https://www.dynatrace.com/hub/detail/ai-and-llm-observability/?filter=ai-ml-observability) solution, Dynatrace brings End-to-End visibility to user interactions, prompt flows, and AI/LLM model performance of your Generative AI, agentic, and LLM services.

Setting up full stack observability for your GenAI applications is possible with direct OpenTelemetry instrumentation or with Traceloop's [OpenLLMetry](https://www.traceloop.com/docs/openllmetry/introduction).  Once a application is instrumented with OpenTelemetry or OpenLLMetry, then the OpenTelemetry signals are sent to a Dynatrace OTLP API direct or via an OpenTelemetry collector.

Below is a video for what to expect once configured. 

### Video

This [YouTube Video](https://www.youtube.com/watch?v=chuG-doRA1w) shows what the traces and metrics look like within Dynatrace AI Observability App that provide comprehensive end-to-end insights.

# Getting Started

This [repository](https://github.com/dynatrace-ace/perform-2026-nvidia-workshop/tree/main) is a self-guided demo for how to build a secure, enterprise-grade AI agent is incapsulated within a simply Python application built using:
* [NVIDIA NeMo Agent Toolkit](https://docs.nvidia.com/nemo/agent-toolkit/) 
* NVIDIA [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) 
* [streamlit](https://www.streamlit.io) open-source app framework

All of the observability telemetry of traces, logs, and metrics are collected using the [Dynatrace distribution of the OpenTelemetry Collector](https://docs.dynatrace.com/docs/ingest-from/opentelemetry/collector) for analysis within [Dynatrace](https://www.dynatrace.com).
