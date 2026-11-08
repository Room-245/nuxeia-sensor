# Nuxeia Agentes, signed

The Mac app «Nuxeia Agentes» connects a computer's coding agents to a company in Nuxeia. Install it from the
company's Nuxeia, at `/agents`, not from here.

The release `mac` holds each build of the app signed with the Developer ID of team `S6R3T94PLB` and notarized by
Apple, one zip per build, named by the SHA-256 of what it signs. The platform's image build fetches the zip that
matches the app it compiled, checks that only the signature differs, and serves it. The code is private; this
repository holds only those zips.
