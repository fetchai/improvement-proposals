# Fetch.ai Improvement Proposals (FIPs)

Fetch.ai Improvement Proposals (FIPs) describe standards for the Fetch.ai platform, including core protocol specifications, client APIs, agent specifications and APIs, and contract standards.

# Contributing

 1. Review the [FIP template](fip-template.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your FIP to your fork of the repository, ensuring that it conforms to the template. 
 4. Submit a Pull Request to the [FIPs repository](https://github.com/fetchai/improvement-proposals).
 

Your first PR should be a first draft of the final FIP. It must meet the formatting criteria. An editor will manually review the first PR for a new FIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the FIP as a whole.

If your FIP requires images, the image files should be included in a subdirectory of the `assets` folder for that FIP as follows: `assets/fip-N` (where **N** is to be replaced with the FIP number). When linking to an image in the FIP, use relative links such as `../assets/fip-1/image.png`.

When you believe your FIP is mature and ready to progress past the draft phase, you should do one of two things:

 - **For a Standards Track FIP of type Core**, ask to have your issue added to the agenda of an upcoming Fetch developer meeting, where it can be discussed for inclusion in a future hard fork. If implementers agree to include it, the FIP editors will update the state of your FIP to 'Accepted'.
 - **For all other FIPs**, open a PR changing the state of your FIP to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the FIP - they may close the PR and request that you fix the issues in the draft before trying again.

# FIP Status Terms

* **Draft** - a FIP that is undergoing rapid iteration and changes.
* **Under Review** - a FIP that is done with its initial iteration and ready for review by a wide audience.
* **Accepted** - a core FIP that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author. The process for Fetch.ai developers to decide whether to encode a FIP into their clients as part of a hard fork is not part of the FIP process. If such a decision is made, the FIP will move to final.
* **Final (non-Core)** - a FIP that has been in **Accepted** for at least 2 weeks and any technical changes that were requested have been addressed by the author.
* **Final (Core)** - a FIP that the Fetch.ai developers have decided to implement and release in a future hard fork or has already been released in a hard fork. 

# Preferred Citation Format

The canonical URL for a FIP that has achieved draft status at any point. For example, the canonical URL for FIP-0 is [?]/fip-0.
