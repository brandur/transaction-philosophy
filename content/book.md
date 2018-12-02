+++
title = "The philosophy of resilience & transaction-oriented software"
date = 2018-09-03T22:42:15-07:00
+++

Software powers the world.

If software has one flaw though, it's reliability. Whether
it's crashing on the last step of patient questionnaire you
fill out on a tablet at your doctor's office, loading
spinners that start but never stop as you're loading your
bank's dashboard, or mysterious unexplained failures as you
try to finish checking in at an airline, we're conditioned
to expect software to fail as often as we expect it to
succeed.

We can only generalize about why software doesn't work as
well as we wish it did, but one thing that's certainly not a
factor is cost. Software written by multi-billion dollar
enterprises is often less reliable than that written by
individuals. An infamous failure from recent years was the
development of HealthCare.gov, a project that with
significant technology challenges from the day it launched
that prevented users from signing up for health insurance,
despite having an estimated cost of $1.7 billion.

So why does software fail? There are many reasons, but none
of them are a smoking gun. Famous technologists like Alan
Kay have speculated that the primitives we use to build it
are too low-level -- the primitives exposed by libraries
are almost universally more akin to letting us shift bits
around than manipulate the complex domain logic that powers
are businesses and projects, forcing us to reinvent the
wheel again and again.

The popularity of interpreted languages like JavaScript,
Python, and Ruby is undoubtedly somewhat of a factor. They
make building small things easy, but fail to provide strong
guarantees around typing and 

Still others blame our processes and structures. While
workers and companies in other industries where lives may
be at risk like medicine, avionics, or civil engineering
must obtain difficult accreditations and comply with rigorous codes,
software practitioners can often 

There are many reasons for this

# Database fundamentals

# Safety at steady state

# ACID

# Consistency and constraints

# Writing applications

## The unit of work

## Connection management

# Postgres

## Bloat

# Scale

## Two-phase commits

## Proprietary systems: Spanner, Aurora

<!--
# vim: set tw=59:
-->
