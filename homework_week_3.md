#General problems with input domain partitions#

In general, the problems in the computation or information processing for a given input can
generally fall into two categories:
Ambiguity or under-defined processing for some given input: Some input values or
test points in the input domain cannot be handled by the program unit under testing.
In other words, these test points are under-dejined, because we cannot find a solution
for them. The most common situations for this kind of problems to occur are when
computational procedures are defined for individual sub-domains, but these subdomains
do not cover the complete input domain, thus creating ambiguity for some
input. The practitioners often refer to this as having “holes” in the input domain.
Contradiction or over-defined processing for some given input: In contrast to the
above, some input values or test points have contradictory computation associated
with them, or are over-defined. Most of such cases indicate problems in the product
specification or in the implementation, which result in different output for the same
input or the system behaves incorrectly, such as fail to stop computation because
it cannot resolve the conflicting results. The most common situations for this kind
of problems to occur is when computational procedures are defined for individual
sub-domains, but some of these subdomains overlap with one another, thus causing
contradictions.
It has been observed both by practitioners and researchers that the above problems are
most likely to happen at boundaries as discussed below.
