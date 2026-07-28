FROM mcr.microsoft.com/devcontainers/python:1-3.12-bookworm

# Keep the toolchain reproducible and source uv from its official image.
COPY --from=ghcr.io/astral-sh/uv:0.10.11 /uv /uvx /bin/

ENV UV_LINK_MODE=copy

