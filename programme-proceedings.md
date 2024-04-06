---
layout: page
title: Programme and Proceedings
nav_order: 40
permalink: /programme-proceedings
---

# PLACES 2024 Programme and Proceedings

{: .proceedings }
The PLACES 2024 proceedings are published in [volume 401 of EPTCS](http://dx.doi.org/10.4204/EPTCS.401).

**6 April 2024**<br>
**[Parc Alvisse Hotel](https://maps.app.goo.gl/7JXZ9afgpbw4zPk86), Room: Holenfells**
{:style="font-size:1.5em;"}

<table id="programme">
    <tr>
        <td class="time">8:00-9:00</td>
        <td colspan="2">Arrival and registration</td>
    </tr>
    <tr>
        <td class="time">9:00-9:10</td>
        <td colspan="2">Opening of PLACES 2024</td>
    </tr>
    <tr class="keynote">
        <td class="time">9:10-10:00</td>
        <td><strong>Keynote talk</strong></td>
        <td>
          <strong><a href="http://www.pm.inf.ethz.ch/people/personal/pmueller-pers.html">Peter Müller</a></strong>,
          ETH Zurich, CH.<br>
          <strong><em>Verified Secure Routing</em></strong>
        </td>
    </tr>
    <tr class="break">
        <td class="time">10:00-10:30</td>
        <td colspan="2">Coffee break</td>
    </tr>
    <tr>
        <td class="time">10:30-11:05</td>
        <td rowspan="3">Session:<br>Networking and Semantics<br><br>Chair: Felix Stutz</td>
        <td>
          Samuel Cavoj, Ivan Nikitin, Colin Perkins and Ornela Dardha.<br>
          <em>Session types for the transport layer: towards an implementation of TCP</em>
        </td>
    </tr>
    <tr>
        <td class="time">11:05-11:40</td>
        <td>
          Simon Fowler, Philipp Haller, Roland Kuhn, Sam Lindley, Alceste Scalas and Vasco T. Vasconcelos.<br>
          <em>Behavioural Types for Heterogeneous Systems (Position Paper)</em>
        </td>
    </tr>
    <tr>
        <td class="time">11:40-12:15</td>
        <td>
          Ilaria Castellani and Paola Giannini.<br>
          <em>Towards a semantic characterisation of global type well-formedness</em>
        </td>
    </tr>
    <tr class="break">
        <td class="time">12:30-14:00</td>
        <td colspan="2">Lunch</td>
    </tr>
    <tr class="keynote">
        <td class="time">14:00-14:50</td>
        <td><strong>Keynote talk</strong></td>
        <td>
          <strong><a href="http://www.di.unito.it/~dezani/">Mariangiola Dezani-Ciancaglini</a></strong>,
          Università di Torino, IT.<br>
          <strong><em>Simple MultiParty Sessions</em></strong>
        </td>
    </tr>
    <tr class="break">
        <td class="time">14:50-15:00</td>
        <td colspan="2">Mini break</td>
    </tr>
    <tr>
        <td class="time">15:00-15:35</td>
        <td rowspan="2">Session:<br>Session subtyping<br><br>Chair: Alceste
        Scalas</td>
        <td>
          Thien Udomsrirungruang and Nobuko Yoshida.<br>
          <em>Three Subtyping Algorithms for Binary Session Types and their Complexity Analyses</em>
        </td>
    </tr>
    <tr>
        <td class="time">15:35-16:00</td>
        <td>
          Elaine Li, Felix Stutz and Thomas Wies.<br>
          <em>Multiparty Session Type Projection and Subtyping with Automata</em>
        </td>
    </tr>
    <tr class="break">
        <td class="time">16:00-16:30</td>
        <td colspan="2">Coffee break</td>
    </tr>
    <tr>
        <td class="time">16:30-17:05</td>
        <td rowspan="3">Session:<br>Session-typed programming<br><br>Chair:
        Raymond Hu</td>
        <td>
          Pedro Ângelo, Atsushi Igarashi and Vasco Vasconcelos<br>
          <em>Session-typed Metaprogramming</em>
        </td>
    </tr>
    <tr>
        <td class="time">17:05-17:30</td>
        <td>
          Lasse Nielsen and Nobuko Yoshida.<br>
          <em>Hapi - Implementing the asynchronous &#960;-calculus with multiparty session types</em>
        </td>
    </tr>
    <tr>
        <td class="time">17:30-17:55</td>
        <td>
          Walid Nawfal Sabihi, Martin Vassor and Nobuko Yoshida.<br>
          <em>Multiparty Session Type Inference for a Rust DSL</em>
        </td>
    </tr>
    <tr>
        <td class="time">17:55-18:00</td>
        <td colspan="2">Closing</td>
    </tr>
</table>

<hr>

<p>
<a name="keynote1"></a>
<strong>Keynote Talk:</strong> <em>Verified Secure Routing</em>
</p>

<p>
<a href="http://www.pm.inf.ethz.ch/people/personal/pmueller-pers.html">Peter Müller</a> <em>(ETH Zurich, CH)</em>
</p>

<p>
SCION is a new Internet architecture that addresses many of the security vulnerabilities of today’s Internet. Its clean-slate design provides, among other properties, route control, failure isolation, and multi-path communication. The verifiedSCION project is an effort to formally verify the correctness and security of SCION. It aims to provide strong guarantees for the entire architecture, from the protocol design to its concrete implementation. The project uses stepwise refinement to prove that the protocol withstands increasingly strong attackers. The refinement proofs assume that all network components such as routers satisfy their specifications. This property is then verified separately using deductive program verification in separation logic. This talk will give an overview of the verifiedSCION project and explain, in particular, how we verify code-level properties such as memory safety, I/O behavior, and information flow security.
</p>


<hr>

<p>
<a name="keynote2"></a>
<strong>Keynote Talk:</strong> <em>Simple MultiParty Sessions</em>
</p>

<p>
<a href="http://www.di.unito.it/~dezani/">Mariangiola Dezani-Ciancaglini</a> <em>(Università di Torino, IT)</em>
</p>

<p>
Simple MultiParty Sessions (SMPS) do not have channels, session initiators and the distinction between compile time and run time syntax. 
They are based only on participant names and input/output processes. They are equipped with global types without requiring projections and local types.
In this presentation we will discuss pros and cons of SMPS. On the good side SMPS allow to easily describe internal delegation, partial typing and session composition.
On the bad side SMPS are less espressive than standard  MultiParty Sessions. In particular interleaved sessions with crossing delegations cannot be represented. 
</p>
