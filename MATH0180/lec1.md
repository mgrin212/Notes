# First Real Lecture

<ins>from last time:</ins>
- defined vectors and scalars in $\mathbb{R}^2$ and $\mathbb{R}^3$
- defined how to add/subtract/scale vectors
- defined the magnitude(length) of a vector
$$
|\langle a,b \rangle| = \sqrt{a^2 + b^2}
$$
$$
|\langle a,b,c \rangle | = \sqrt{a^2 + b^2 + c^2 }
$$
$$
\vec{v} + \vec{w} = \vec{w} + \vec{v}
$$

## Direction
- A unit vector is a vector with magnitude 1
    - a unit vector in the direction of $\vec{v}$ would be $\vec{v} \over |\vec{v}|$
    - ex: $\langle 2,1,4 \rangle$ has a magnituse $\sqrt{2^2 + 1^2 + 4^2} = \sqrt{21} $, so the vector points in the direction $1 \over \sqrt{21}$ $\langle 2,1,4 \rangle$
- In $\mathbb{R}^2$, we describe a direction by its angle
    - $\vec{v} = \langle rcos\theta, rsin\theta \rangle$

## Dot Product: $\vec{v} \cdot \vec{w}$ (Scalar Product)
a) $\vec{v} \cdot \vec{w} = |\vec{v}||\vec{w}|cos\theta$
where $\theta$ is the angle between $\vec{v}$ and $\vec{w}$

$\iff$

b) $\langle a_1,b_1 \rangle \cdot \langle a_2,b_2 \rangle = a_1 a_2 + b_1b_2$

### Properties
- $\vec{v} \cdot \vec{v} = |\vec{v}|^2$
    - $\langle a,b,c \rangle \cdot \langle a,b,c \rangle = a^2 + b^2 + c^2 = (\sqrt{a^2 + b^2 + c^2})^2$
- $\vec{v} \cdot \vec{w} = \vec{w} \cdot \vec{v}$
- $\vec{u} \cdot (\vec{v} + \vec{w}) = \vec{u} \cdot \vec{v} + \vec{u} \cdot \vec{w}$
- $c(\vec{v} \cdot \vec{w}) = (c\vec{v}) \cdot \vec{w} = \vec{v} \cdot (c \vec{w})$

### Finding the angle between two vectors:
- $\vec{v} \cdot \vec{w} = |\vec{v}||\vec{w}||cos\theta$
$$
cos\theta = \frac{\vec{v} \cdot \vec{w}}{|\vec{v}||\vec{w}|}
$$
$$
\theta = arccos(\frac{\vec{v} \cdot \vec{w}}{|\vec{v}||\vec{w}|})
$$
- the range of arccos is 0-$\pi$
- $\langle 1,2,3 \rangle \cdot \langle 4,5,6 \rangle$
- $\theta = arccos(\frac{32}{\sqrt{1+4+9} + \sqrt{16+25+36}})$

### $90^0$
- if two vectors have an angle of $90^0$ between them, we call them orthogonal
- because $cos(90^0) = 0$, the dot product of orthogonal vectors is 0
- $\vec{v},\vec{w}$ are orthogonal $\iff$ $\vec{v} \cdot \vec{w} = 0$

### Projections
How much of one vector points in the direction of the other?

Scalar projection: length of indicated vector in direction of other vector

vector projection: split the vector into parallel and perpendicular component
