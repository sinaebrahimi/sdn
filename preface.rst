Preface 
=======

The Internet is in the midst of a transformation, one that moves away
from bundled proprietary devices, and instead embraces disaggregating
network hardware (which becomes commodity) from the software that
controls it (which scales in the cloud). The transformation is
generally known as *Software-Defined Networking (SDN)*, but because it
is disrupting the marketplace, it is challenging to untangle business
positioning from technical fundamentals, from short-term engineering
decisions. This book provides such an untangling, where the most
important thing we hope readers take away is an understanding of an
SDN-based network as a scalable distributed system running on
commodity hardware.

Anyone who has taken an introductory networking class recognizes the
protocol stack as the canonical framework for describing the
network. Whether that stack has seven layers or just three, it shapes
and constrains the way we think about computer networks. Textbooks are
organized accordingly. SDN suggests an alternative world-view, one
that comes with a new software stack. This book is organized around
that new stack, with the goal of presenting a top-to-bottom tour of
SDN without leaving any significant gaps that the reader might suspect
can only be filled with magic or proprietary code. *We invite you do
the hands-on programming exercises included at the end of the book to
prove to yourself that the software stack is both real and complete.*

An important aspect of meeting this goal is to use open source. We do
this in large part by taking advantage of two community-based
organizations that are leading the way. One is the *Open Compute
Project (OCP)*, which is actively specifying and certifying commodity
hardware (e.g., bare-metal switches) upon which the SDN software stack
runs. The second is the *Open Networking Foundation (ONF)*, which is
actively implementing a suite of software components that can be
integrated into an end-to-end solution. There are many other players
in this space—from incumbent vendors to network operators, startups,
standards bodies, and other open source projects—each offering varied
interpretations of what SDN *is* and *is not*. We discuss these other
perspectives and explain how they fit into the larger scheme of
things, but we do not let them deter us from describing the full
breadth of SDN. Only time will tell where the SDN journey takes us,
but we believe it is important to understand the scope of the
opportunity.

This book assumes a general understanding of the Internet, although a
deeper appreciation for the role switches and routers play forwarding
ethernet frames and IP packets is helpful. Links to related background
information are included to help bridge any gaps.

This book is a work-in-progress, with updates, clarifications, and new
material added continuously. For example, the latest version (v2.0)
includes new chapters on *Network Virtualization* (Chapter 8) and
*Access Networks* (Chapter 9).  We are eager to hear your feedback and
suggestions on how we can continue to improve this book.

Acknowledgements
----------------

The software described in this book is due to the hard work of the ONF
engineering team and the open source community that works with
them. We acknowledge their contributions, with a special thank-you to
Yi Tseng, Max Pudelko, and Charles Chan for their contributions to the
tutorials that this book includes as hands-on exercises. We also thank
Charles Chan, Jennifer Rexford, Nick McKeown, Kentaro Ebisawa,
Motonori Shindo, and Sina Ebrahimi for their comments and feedback.

.. To include in epub and printed versions

The cover photo of the Ueno Station (Tokyo) is
by `Athena Lam <https://unsplash.com/@thecupandtheroad>`__
on `Unsplash <https://unsplash.com>`__.

| Larry Peterson, Carmelo Cascone, Brian O'Connor, Thomas Vachuska, and Bruce Davie
| November 2021

