doc.sp
======

NetKernel Software Process Book (urn:org:netkernel:doc:content:process)

Purpose
=======

This Software Process Book is a collection of best practice knowledge captured
from both 1060 Research and community collaboration. It's scope is broad - to
document knowledge of how to architect, design, implement, test, tune, take to
production, manage and maintain systems developed with 1060 NetKernel using the
Resource Oriented Computing (ROC) approach.

We welcome your input. Everything from typos, corrections and suggestions to
ownership and writing of pages or complete sections.

The aim is to start shipping versions of this book in the NetKernel distribution
and make ready-to-read updates available on the apposite repository.

How to install
==============

1) Download and install NetKernel
2) Checkout this repository
3) Edit [netkernel_install]/etc/modules.xml and add the line:
   <module>[full path to git repository]</module>
4) Boot netkernel
5) View this page in your browser:
   http://localhost:1060/book/view/book:software:process/