Importing CWR Acknowledgements
==============================

Societies and administrative agencies (that handle CWR registrations for some societies) will send acknowledgement files, which are also in CWR format. You may receive more than one acknowledgement file for every CWR file you delivered.

Importing CWR acknowledgement files into Django-Music-Publisher is very simple, just select ``Add`` in the ``CWR ACK import``, choose the file and save. A brief report will be shown, and there will be an additional line in ``Change Work views`` for every work in the acknowledgement file.

There is also a preview of the CWR acknowledgement with basic syntax highlighting. Each ACK transaction has an ACK header,
followed by the data from your registration with optionally additional MSG records. The receiving party should only return the data they have
actually used, but many societies just return exactly what you sent.

In the ACK record, the last two letters are the most important, they show the status of the transaction. More information can be found in the MSG records, they usually refer to the first record below.

Dealing with issues is not covered by this user manual, you must consult the official CWR documentation as well as inquiry with your society.
If you are instructed to contact the software vendor, according to the licence, it is you, not the creator of
this software.

There are two external tools freely available that may assist you:

* `ACK Tool <https://matijakolaric.com/free/cwr-x-ack-tool>`_ that creates summaries of CWR acknowledgement files

* `CWR Syntax Highlighter <https://matijakolaric.com/free/cwr-syntax-highlighter/>`_ with complete syntax highlighting

Please note that acknowledgement files differ greatly from one society to the next, which makes it hard to create a general tool.

Django-Music-Publisher currently only supports CWR 2.1 acknowledgement files with experimental support for CWR 3.0.
