# process-shared-csp
CSP files for the paper "Verifying Correctness of Shared Channels in a Cooperatively Scheduled Process-Oriented Language"

channel-spec.csp: CSP specification for the general N_TO_M_GENERIC_CHANNEL specification.
channel.csp: CSP for the back-bone of a channel.
monitor.csp: CSP for a monitor.
queue.csp: CSP for a queue.
restricted-shared-channel.csp: CSP processes for restricted one-to-many, many-to-one, and many-to-many channel systems (implementation).
scheduler.csp: CSP for the ProcessJ scheduler.
variables.csp: CSP for the state processses.

1-to-2.csp: assertions for testing one-to-many channels (one writer, two readers)
1-to-3.csp: assertions for testing one-to-many channels (one writer, three readers)
2-to-1.csp: assertions for testing many-to-one channels (two writers, one reader)
3-to-1.csp: assertions for testing one-to-many channels (three writers, one reader)
2-to-2.csp: assertions for testing many-to-many channels (two writers, two readers)
