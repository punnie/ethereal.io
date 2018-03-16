---
layout: post
title:  "If no tool suits your need, maybe it's you"
date:   2017-12-20 16:16:01 -0000
tags: devops practices
---

If you ever find yourself searching for COTS tools to do something trivial and reach the conclusion that no available tool fits your purpose, consider it may not be the tools’ fault, it might be you.

It might mean your method is done in a non-standard way, and while sometimes that’s a clear necessity, other times it’s not.

Whenever this situation arises it’s a great opportunity to research a bit on why it happens, instead of directly jumping to conclusions.

For instance: you end up concluding that no tool available on the market can correctly deploy your application. This might mean that your application has convoluted deploy logic intrinsic to the domain that will never fit the general case, and that you’ll need to invest time in building a deploy tool that ensures correctness and reliability.

However, it might also mean that there’s unnecessary complexity in your deploy logic. That complexity may have come from legacy, or poorly informed decisions. It may uncover wrong assumptions in the organisation about how deploying an application works, or what concerns it should address. It’s a great excuse to devote some time in finding out how others do it, and why, and if your case fits the general assumptions. Consider it may be worth spending the time you’d allocate building a solution into changing the current process and assumptions. And also don’t forget that standard paths get more attention from the general public, which means more people facing your problems, and a greater deal of effort from the community into solving the problem for everyone.

Concluding: do your research before attempting to reinvent the wheel. Sometimes you end up finding out it’s worth it as the available tooling lacks maturity or you’re trying to push the envelope on new and innovative ways to revolutionise and disrupt that space. But it might also reveal a great learning opportunity that will amend wrong assumptions and teach you concerns you hadn’t considered.

Sometimes it’s not them, it’s you.
