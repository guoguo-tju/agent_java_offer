# Agent Java Offer Open Source Migration Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** 在新项目中建立一份可开源发布的 Java/AI 面试资料库骨架，并迁入 `interview_prep_v2` 的内容作为公开版主内容。

**Architecture:** 目标项目使用文档仓库结构，核心资料统一放在 `docs/interview_prep/` 下；原始资料仓库不改动。第一阶段只做复制、相对链接修复和开源待处理清单，不做 GitHub 发布与敏感语义全面匿名化。

**Tech Stack:** Markdown, shell, Python 3

---

### Task 1: 建立目标项目骨架

**Files:**
- Create: `README.md`
- Create: `.gitignore`
- Create: `LICENSE`
- Create: `DISCLAIMER.md`
- Create: `docs/open-source-preflight-checklist.md`
- Create: `docs/interview_prep/**`

- [ ] 建立目录骨架与基础元信息文件
- [ ] 复制 `interview_prep_v2` 到 `docs/interview_prep`
- [ ] 将绝对路径替换为仓库内相对路径
- [ ] 生成第一版开源前待处理清单
- [ ] 校验不存在本机绝对路径链接
