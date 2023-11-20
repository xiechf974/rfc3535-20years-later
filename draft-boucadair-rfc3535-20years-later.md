---
title: "Ref"
abbrev: "RFC 3535, 20 Years Later"
category: info

docname: draft-boucadair-rfc3535-20years-later-latest
submissiontype: IETF
number:
date:
consensus: true
v: 3
# area: AREA
# workgroup: WG Working Group
keyword:
 - network management
 - future networks

author:
 -
   fullname: Mohamed Boucadair
   organization: Orange
   email: mohamed.boucadair@orange.com

normative:

informative:


--- abstract

The IAB has organized an important workshop
to establish a dialog between network operators and
protocol developers, and to guide the IETF focus on work
regarding network management.  That outcome of that workshop
was documented in "IAB Network Management Workshop" (RFC 3535)
and was instrumental for developing NETCONF and YANG.

20 years later, it is time to evaluate what has been achieved since then
and identify the operational barriers for making these
technologies widely implemented. Also, this document intends to capture new
requirements for network management operations.

--- middle

# Introduction

The IAB has organized an important workshop (June 4-June 6, 2002)
to establish a dialog between network operators and
protocol developers, and to guide the IETF focus on work
regarding network management.  That outcome of that workshop
was documented in "IAB Network Management Workshop" {{?RFC3535}}
which was instrumental for developing NETCONF {{?RFCR6241}}, YANG {{?RFC6020}}{{?RFC7950}}, and RESTCONF {{?RFC8040}}.

20 years later, new requirements on network management operations requirements are emerging from the operators. This document intends to capture these requirements

Early version of the document includes many placeholders on purpose as it intends to collect inputs.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Summary of Achievements Since RFC 3535

TBC.

# Assessment of RFC 3535 Recommendations

{{Section 6 of ?RFC3535}} includes the following recommendations:

   1.  The workshop recommends that the IETF stop forcing working groups
       to provide writable MIB modules.  It should be the decision of
       the working group whether they want to provide writable objects
       or not.

       **Status Update**: In 2014, the IESG published a statement Writable MIB Module, which states that:
         > SNMP MIB modules creating and modifying configuration state should only be produced by working groups in cases of clear utility and consensus to use SNMP 
 write operations for configuration, and in consultation with the OPS ADs/MIB doctors.

   3.  The workshop recommends that a group be formed to investigate why
       current MIB modules do not contain all the objects needed by
       operators to monitor their networks.

       **Status Update**: xxx

   4.  The workshop recommends that a group be formed to investigate why
       the current SNMP protocol does not satisfy all the monitoring
       requirements of operators.

       **Status Update**: xxx

   5.  The workshop recommends, with strong consensus from both protocol
       developers and operators, that the IETF focus resources on the
       standardization of configuration management mechanisms.

       **Status Update**: NETCONF, RESTCONF, CORECONF, YANG.

   6.  The workshop recommends, with strong consensus from the operators
       and rough consensus from the protocol developers, that the
       IETF/IRTF should spend resources on the development and
       standardization of XML-based device configuration and management
       technologies (such as common XML configuration schemas, exchange
       protocols and so on).

       **Status Update**: OK.

   7.  The workshop recommends, with strong consensus from the operators
       and rough consensus from the protocol developers, that the
       IETF/IRTF should not spend resources on developing HTML-based or
       HTTP-based methods for configuration management.

       **Status Update**: The IETF deviated from this recommendation, e.g., RESTCONF {{?RFC8040}} or CoAP Management Interface (CORECONF) {{?I-D.ietf-core-comi}}.

   8.  The workshop recommends, with rough consensus from the operators
       and strong consensus from the protocol developers, that the IETF
       should continue to spend resources on the evolution of the
       SMI/SPPI data definition languages as being done in the SMIng
       working group.

       **Status Update**: SMIng WG was concluded in 2003-04-04.

   9.  The workshop recommends, with split consensus from the operators
       and rough consensus from the protocol developers, that the IETF
       should spend resources on fixing the MIB development and
       standardization processs.

       **Status Update**: The IETF dedicated some resources to fix some
       SNMP shortcomings with a focus on security (e.g., Transport Layer Security (TLS) Transport Model for
       the SNMP {{?RFC6353}} or {{?RFC9456}}, HMAC-SHA-2 Authentication Protocols in User-Based Security Model (USM) for SNMPv3 {{?RFC7860}}).

{{Section 6 of ?RFC3535}} also includes the following but without tagging them as recommendations:

   1.  The workshop had split consensus from the operators and rough
       consensus from the protocol developers, that the IETF should not
       focus resources on CIM extensions.

       **Status Update**: The IETF didn't dedicate any resources on CIM extensions.

   2.  The workshop had rough consensus from the protocol developers
       that the IETF should not spend resources on COPS-PR development.
       So far, the operators have only very limited experience with
       COPS-PR.  In general, however, they felt that further development
       of COPS-PR might be a waste of resources as they assume that
       COPS-PR does not really address their requirements.

       **Status Update**: The IETF has reclassified COPS Usage for Policy Provisioning {{?RFC3084}}
       to Historic status.

   3.  The workshop had rough consensus from the protocol developers
       that the IETF should not spend resources on SPPI PIB definitions.
       The operators had rough consensus that they do not care about
       SPPI PIBs.

       **Status Update**: The IETF has reclassified Structure of Policy Provisioning Information {{?RFC3159}}, as well as
       three Policy Information Bases ({{?RFC3317}}, {{?RFC3318}}, and {{?RFC3571}}) to 
       Historic status.

# Some Observations

## Fragmented Ecosystem

The current YANG device models ecosystem is fragmented: some
standards models are defined in the IETF while similar ones are
defined in other fora such as Openconfig.  Unlike service and
network models, IETF-defined device models are not widely
implemented. There is a need to rationalize this space and
avoid redundant efforts.

# Need for Profiling

Many NETCONF-related tools are (being) specified by the IETF,
but these tools are not widely supported (e.g., Push). Editing a
profile document with a set of recommendations about core/key
features with the appropriate justification will help the
emergence of more implementations that meet the operators’
needs. Examples of such profile documents are RFCs that
were published by the behave WG {{?BCP127}}.

Likewise, reassess the value of some IETF proposals vs. competing/emerging solution would be useful.

# Lack of Agile Process for YANG Modules

RFCs might not be suited for documenting YANG modules. In the meantime, there is a need for
"reference models" and "sufficiently stable models". An
hybrid approach might be investigated for documenting IETF-
endorsed YANG modules, such as considering an RFC to
describe the initial module sketch and objectives and an
official IETF repository for maintaining intermediate YANG
versions.

# Security Considerations

TBC


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
