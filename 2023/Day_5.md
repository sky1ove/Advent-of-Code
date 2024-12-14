

``` python
pip install 'advent-of-code-data[nb]'
```

    Collecting advent-of-code-data[nb]
      Downloading advent_of_code_data-2.0.4-py3-none-any.whl.metadata (11 kB)
    Requirement already satisfied: beautifulsoup4 in /usr/local/lib/python3.10/dist-packages (from advent-of-code-data[nb]) (4.12.3)
    Collecting pebble (from advent-of-code-data[nb])
      Downloading Pebble-5.1.0-py3-none-any.whl.metadata (3.6 kB)
    Requirement already satisfied: urllib3 in /usr/local/lib/python3.10/dist-packages (from advent-of-code-data[nb]) (2.2.3)
    Collecting aocd-example-parser>=2023.2 (from advent-of-code-data[nb])
      Downloading aocd_example_parser-2023.12.20-py3-none-any.whl.metadata (8.9 kB)
    Requirement already satisfied: IPython in /usr/local/lib/python3.10/dist-packages (from advent-of-code-data[nb]) (7.34.0)
    Requirement already satisfied: jupyter-server in /usr/local/lib/python3.10/dist-packages (from advent-of-code-data[nb]) (1.24.0)
    Requirement already satisfied: soupsieve>1.2 in /usr/local/lib/python3.10/dist-packages (from beautifulsoup4->advent-of-code-data[nb]) (2.6)
    Requirement already satisfied: setuptools>=18.5 in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (75.1.0)
    Collecting jedi>=0.16 (from IPython->advent-of-code-data[nb])
      Downloading jedi-0.19.2-py2.py3-none-any.whl.metadata (22 kB)
    Requirement already satisfied: decorator in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (4.4.2)
    Requirement already satisfied: pickleshare in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (0.7.5)
    Requirement already satisfied: traitlets>=4.2 in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (5.7.1)
    Requirement already satisfied: prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0 in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (3.0.48)
    Requirement already satisfied: pygments in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (2.18.0)
    Requirement already satisfied: backcall in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (0.2.0)
    Requirement already satisfied: matplotlib-inline in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (0.1.7)
    Requirement already satisfied: pexpect>4.3 in /usr/local/lib/python3.10/dist-packages (from IPython->advent-of-code-data[nb]) (4.9.0)
    Requirement already satisfied: anyio<4,>=3.1.0 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (3.7.1)
    Requirement already satisfied: argon2-cffi in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (23.1.0)
    Requirement already satisfied: jinja2 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (3.1.4)
    Requirement already satisfied: jupyter-client>=6.1.12 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (6.1.12)
    Requirement already satisfied: jupyter-core!=5.0.*,>=4.12 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (5.7.2)
    Requirement already satisfied: nbconvert>=6.4.4 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (7.16.4)
    Requirement already satisfied: nbformat>=5.2.0 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (5.10.4)
    Requirement already satisfied: packaging in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (24.2)
    Requirement already satisfied: prometheus-client in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (0.21.1)
    Requirement already satisfied: pyzmq>=17 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (24.0.1)
    Requirement already satisfied: Send2Trash in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (1.8.3)
    Requirement already satisfied: terminado>=0.8.3 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (0.18.1)
    Requirement already satisfied: tornado>=6.1.0 in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (6.3.3)
    Requirement already satisfied: websocket-client in /usr/local/lib/python3.10/dist-packages (from jupyter-server->advent-of-code-data[nb]) (1.8.0)
    Requirement already satisfied: idna>=2.8 in /usr/local/lib/python3.10/dist-packages (from anyio<4,>=3.1.0->jupyter-server->advent-of-code-data[nb]) (3.10)
    Requirement already satisfied: sniffio>=1.1 in /usr/local/lib/python3.10/dist-packages (from anyio<4,>=3.1.0->jupyter-server->advent-of-code-data[nb]) (1.3.1)
    Requirement already satisfied: exceptiongroup in /usr/local/lib/python3.10/dist-packages (from anyio<4,>=3.1.0->jupyter-server->advent-of-code-data[nb]) (1.2.2)
    Requirement already satisfied: parso<0.9.0,>=0.8.4 in /usr/local/lib/python3.10/dist-packages (from jedi>=0.16->IPython->advent-of-code-data[nb]) (0.8.4)
    Requirement already satisfied: python-dateutil>=2.1 in /usr/local/lib/python3.10/dist-packages (from jupyter-client>=6.1.12->jupyter-server->advent-of-code-data[nb]) (2.8.2)
    Requirement already satisfied: platformdirs>=2.5 in /usr/local/lib/python3.10/dist-packages (from jupyter-core!=5.0.*,>=4.12->jupyter-server->advent-of-code-data[nb]) (4.3.6)
    Requirement already satisfied: bleach!=5.0.0 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (6.2.0)
    Requirement already satisfied: defusedxml in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (0.7.1)
    Requirement already satisfied: jupyterlab-pygments in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (0.3.0)
    Requirement already satisfied: markupsafe>=2.0 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (3.0.2)
    Requirement already satisfied: mistune<4,>=2.0.3 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (3.0.2)
    Requirement already satisfied: nbclient>=0.5.0 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (0.10.1)
    Requirement already satisfied: pandocfilters>=1.4.1 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (1.5.1)
    Requirement already satisfied: tinycss2 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (1.4.0)
    Requirement already satisfied: fastjsonschema>=2.15 in /usr/local/lib/python3.10/dist-packages (from nbformat>=5.2.0->jupyter-server->advent-of-code-data[nb]) (2.21.1)
    Requirement already satisfied: jsonschema>=2.6 in /usr/local/lib/python3.10/dist-packages (from nbformat>=5.2.0->jupyter-server->advent-of-code-data[nb]) (4.23.0)
    Requirement already satisfied: ptyprocess>=0.5 in /usr/local/lib/python3.10/dist-packages (from pexpect>4.3->IPython->advent-of-code-data[nb]) (0.7.0)
    Requirement already satisfied: wcwidth in /usr/local/lib/python3.10/dist-packages (from prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0->IPython->advent-of-code-data[nb]) (0.2.13)
    Requirement already satisfied: argon2-cffi-bindings in /usr/local/lib/python3.10/dist-packages (from argon2-cffi->jupyter-server->advent-of-code-data[nb]) (21.2.0)
    Requirement already satisfied: webencodings in /usr/local/lib/python3.10/dist-packages (from bleach!=5.0.0->nbconvert>=6.4.4->jupyter-server->advent-of-code-data[nb]) (0.5.1)
    Requirement already satisfied: attrs>=22.2.0 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=5.2.0->jupyter-server->advent-of-code-data[nb]) (24.2.0)
    Requirement already satisfied: jsonschema-specifications>=2023.03.6 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=5.2.0->jupyter-server->advent-of-code-data[nb]) (2024.10.1)
    Requirement already satisfied: referencing>=0.28.4 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=5.2.0->jupyter-server->advent-of-code-data[nb]) (0.35.1)
    Requirement already satisfied: rpds-py>=0.7.1 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=5.2.0->jupyter-server->advent-of-code-data[nb]) (0.22.3)
    Requirement already satisfied: six>=1.5 in /usr/local/lib/python3.10/dist-packages (from python-dateutil>=2.1->jupyter-client>=6.1.12->jupyter-server->advent-of-code-data[nb]) (1.17.0)
    Requirement already satisfied: cffi>=1.0.1 in /usr/local/lib/python3.10/dist-packages (from argon2-cffi-bindings->argon2-cffi->jupyter-server->advent-of-code-data[nb]) (1.17.1)
    Requirement already satisfied: pycparser in /usr/local/lib/python3.10/dist-packages (from cffi>=1.0.1->argon2-cffi-bindings->argon2-cffi->jupyter-server->advent-of-code-data[nb]) (2.22)
    Downloading aocd_example_parser-2023.12.20-py3-none-any.whl (12 kB)
    Downloading advent_of_code_data-2.0.4-py3-none-any.whl (38 kB)
    Downloading Pebble-5.1.0-py3-none-any.whl (36 kB)
    Downloading jedi-0.19.2-py2.py3-none-any.whl (1.6 MB)
       ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 20.8 MB/s eta 0:00:00
    Installing collected packages: pebble, jedi, aocd-example-parser, advent-of-code-data
    Successfully installed advent-of-code-data-2.0.4 aocd-example-parser-2023.12.20 jedi-0.19.2 pebble-5.1.0

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

``` python
import os
os.environ['AOC_SESSION'] = "53616c7465645f5ffc51b1b4030426e2eb3ee5d5406f6e51f3a56c32ca9649e34ee45d8d8faceeb1d781fc4d6352b3ba2c0d868e7c2de79192d8ebb9787d1eca"
```

``` python
from aocd import get_data
from dataclasses import dataclass
```

``` python
data = get_data(day=5,year=2024)
```

``` python
from dataclasses import dataclass

@dataclass
class MyClass:
    src: int
    length: int

    def get_range(self):
        """Get the range as (start, end)."""
        return self.src, self.src + self.length

    def cut_to_overlap(self, reference):
        """Cut this object to fit within the reference object's range."""
        ref_start, ref_end = reference.get_range()
        obj_start, obj_end = self.get_range()

        # Calculate the overlapping range
        overlap_start = max(ref_start, obj_start)
        overlap_end = min(ref_end, obj_end)

        # If there's no overlap, return None
        if overlap_start >= overlap_end:
            return None

        # Create a new object with the overlapping range
        return MyClass(overlap_start, overlap_end - overlap_start)


def get_uncovered_parts(reference_obj, other_objects):
    """Get the parts of the reference object not covered by other objects."""
    ref_start, ref_end = reference_obj.get_range()
    uncovered_parts = []

    # Start with the entire reference range
    current_ranges = [(ref_start, ref_end)]

    # Process all overlapping objects to subtract their ranges from the reference range
    for obj in other_objects:
        obj_start, obj_end = obj.get_range()
        new_ranges = []
        for start, end in current_ranges:
            # No overlap, keep the current range
            if obj_end <= start or obj_start >= end:
                new_ranges.append((start, end))
            else:
                # If overlapping, split into uncovered ranges
                if obj_start > start:
                    new_ranges.append((start, obj_start))
                if obj_end < end:
                    new_ranges.append((obj_end, end))
        current_ranges = new_ranges

    # Convert the remaining ranges into MyClass objects
    for start, end in current_ranges:
        uncovered_parts.append(MyClass(start, end - start))

    return uncovered_parts


# Example usage
reference = MyClass(10, 20)  # Reference object: src=10, length=20
other_objects = [
    MyClass(5, 10),   # Partially overlaps
    MyClass(20, 10),  # Overlaps fully within the reference
    MyClass(30, 10)   # Does not overlap
]

# Get the uncovered parts of the reference object
uncovered_parts = get_uncovered_parts(reference, other_objects)

uncovered_parts
```

    [MyClass(src=15, length=5)]

``` python
overlapping
```

    [MyClass(src=10, length=5),
     MyClass(src=15, length=10),
     MyClass(src=25, length=5)]

``` python
overlapping[0].get_range()
```

    (10, 15)

``` python
from dataclasses import dataclass

@dataclass
class MyClass:
    src: int
    dest: int
    length: int

    def get_range(self):
        """Get the range as (start, end) in the src context."""
        return self.src, self.src + self.length

    def cut_to_overlap(self, reference):
        """Cut this object to fit within the reference object's range."""
        ref_start, ref_end = reference.get_range()
        obj_start, obj_end = self.get_range()

        # Calculate the overlapping range
        overlap_start = max(ref_start, obj_start)
        overlap_end = min(ref_end, obj_end)

        # If there's no overlap, return None
        if overlap_start >= overlap_end:
            return None

        # Calculate the corresponding dest range for the overlap
        overlap_length = overlap_end - overlap_start
        dest_overlap_start = self.dest + (overlap_start - obj_start)

        # Create a new object with the overlapping range in the dest context
        return MyClass(overlap_start, dest_overlap_start, overlap_length)


def get_uncovered_parts(reference_obj, other_objects):
    """Get the parts of the reference object not covered by other objects."""
    ref_start, ref_end = reference_obj.get_range()
    uncovered_parts = []

    # Start with the entire reference range
    current_ranges = [(ref_start, ref_end)]

    # Process all overlapping objects to subtract their ranges from the reference range
    for obj in other_objects:
        obj_start, obj_end = obj.get_range()
        new_ranges = []
        for start, end in current_ranges:
            # No overlap, keep the current range
            if obj_end <= start or obj_start >= end:
                new_ranges.append((start, end))
            else:
                # If overlapping, split into uncovered ranges
                if obj_start > start:
                    new_ranges.append((start, obj_start))
                if obj_end < end:
                    new_ranges.append((obj_end, end))
        current_ranges = new_ranges

    # Convert the remaining ranges into MyClass objects (in src context only)
    for start, end in current_ranges:
        uncovered_parts.append(MyClass(start, None, end - start))

    return uncovered_parts


def separate_and_convert_to_dest(reference_obj, other_objects):
    """Get the overlapping parts in the dest context."""
    overlapping_dest_objects = []

    for obj in other_objects:
        cut_obj = obj.cut_to_overlap(reference_obj)
        if cut_obj:
            overlapping_dest_objects.append(cut_obj)

    return overlapping_dest_objects


# Example usage
reference = MyClass(10, 0, 20)  # Reference object: src=10, dest=0, length=20
other_objects = [
    MyClass(5, 100, 10),   # Partially overlaps
    MyClass(20, 200, 10),  # Overlaps fully
    MyClass(25, 300, 10),  # Does not overlap
]

# Get the overlapping parts converted to dest context
overlapping_dest_objects = separate_and_convert_to_dest(reference, other_objects)

# Get the uncovered parts in src context
uncovered_parts = get_uncovered_parts(reference, other_objects)
```

``` python
overlapping_dest_objects
```

    [MyClass(src=10, dest=105, length=5),
     MyClass(src=20, dest=200, length=10),
     MyClass(src=25, dest=300, length=5)]

``` python
uncovered_parts
```

    [MyClass(src=15, dest=None, length=5)]

``` python
from fastcore.utils import L
```

``` python
lines = L([[50, 98, 2], [52, 50, 48]],[[0, 15, 37], [37, 52, 2], [39, 0, 15]],[[49, 53, 8], [0, 11, 42], [42, 0, 7], [57, 7, 4]],[[88, 18, 7], [18, 25, 70]],[[45, 77, 23], [81, 45, 19], [68, 64, 13]],[[0, 69, 1], [1, 0, 69]],[[60, 56, 37], [56, 93, 4]])
```

``` python
object_lines = lines.map(lambda x: L(x).starmap(lambda dest,src,length: MyClass(src,dest,length)))
object_lines
```

    (#7) [[MyClass(src=98, dest=50, length=2), MyClass(src=50, dest=52, length=48)],[MyClass(src=15, dest=0, length=37), MyClass(src=52, dest=37, length=2), MyClass(src=0, dest=39, length=15)],[MyClass(src=53, dest=49, length=8), MyClass(src=11, dest=0, length=42), MyClass(src=0, dest=42, length=7), MyClass(src=7, dest=57, length=4)],[MyClass(src=18, dest=88, length=7), MyClass(src=25, dest=18, length=70)],[MyClass(src=77, dest=45, length=23), MyClass(src=45, dest=81, length=19), MyClass(src=64, dest=68, length=13)],[MyClass(src=69, dest=0, length=1), MyClass(src=0, dest=1, length=69)],[MyClass(src=56, dest=60, length=37), MyClass(src=93, dest=56, length=4)]]

``` python
seed = [79,14,55,13]
```

``` python
def convert_for_next_round(objects):
    """
    Convert objects for the next round by updating src to dest,
    and clearing dest (if dest is None, src remains unchanged).
    """
    converted_objects = []
    for obj in objects:
        new_src = obj.dest if obj.dest is not None else obj.src
        converted_objects.append(MyClass(src=new_src, dest=None, length=obj.length))
    return converted_objects

def process_round(current_objects, new_objects):
    """
    Process a single round of comparison, including overlap and uncovered calculations.
    """
    # Treat the current objects as the reference for this round
    reference_objects = current_objects

    # Find overlapping parts in the dest context
    merged_results = []
    for ref_obj in reference_objects:
        ref_overlapping = separate_and_convert_to_dest(ref_obj, new_objects)
        ref_uncovered = get_uncovered_parts(ref_obj, new_objects)

        # Merge overlapping and uncovered parts for this reference object
        merged_results.extend(ref_overlapping + ref_uncovered)

    return merged_results



# Combine overlapping and uncovered objects for conversion
converted_objects = convert_for_next_round(overlapping_dest_objects + uncovered_parts)

# New objects for the next round
new_objects_next_round = [
    MyClass(100, 400, 10),
    MyClass(110, 410, 10),
    MyClass(120, 420, 10),
]

# Process the next round
out = process_round(converted_objects, new_objects_next_round)
```

``` python
out
```

    [MyClass(src=105, dest=405, length=5),
     MyClass(src=200, dest=None, length=10),
     MyClass(src=300, dest=None, length=5),
     MyClass(src=15, dest=None, length=5)]

``` python
def process_all_rounds(rounds, references):
    """
    Process all rounds of conversion with multiple references.

    Args:
        rounds: List of lists of MyClass objects (7 rounds of objects).
        references: List of MyClass reference objects.

    Returns:
        Dictionary: Overlapping objects for each reference (keyed by their src values).
    """
    results = {}  # Dynamically store results for each reference

    for i, round_objects in enumerate(rounds):
        print(f"Processing Round {i + 1}...")

        # Process each reference independently
        new_references = []
        for ref in references:
            # Ensure the reference's src is in results
            if ref.src not in results:
                results[ref.src] = []

            overlapping, uncovered = process_round([ref], round_objects)

            # Append overlapping objects to results for this reference
            results[ref.src].extend(overlapping)

            # Update references for the next round
            # Convert overlapping objects for next round (src = dest)
            converted_overlapping = convert_for_next_round(overlapping)
            new_references.extend(converted_overlapping)

            # Keep uncovered parts as they are
            new_references.extend(uncovered)

        # Update references for the next round
        references = new_references

    return results


def process_all_rounds(rounds, references):
    """
    Process all rounds of conversion with multiple references.

    Args:
        rounds: List of lists of MyClass objects (7 rounds of objects).
        references: List of MyClass reference objects.

    Returns:
        Dictionary: Overlapping objects for each reference (keyed by their src values).
    """
    results = {}  # Dynamically store results for each reference

    for i, round_objects in enumerate(rounds):
        print(f"Processing Round {i + 1}...")

        # Process each reference independently
        new_references = []
        for ref in references:
            print(ref,'aa')
            # Ensure the reference's src is in results
            if ref.src not in results:
                results[ref.src] = []

            # Process the round and get merged results (both overlapping and uncovered)
            merged_results = process_round([ref], round_objects)

            # Append all results to the corresponding reference's results
            results[ref.src].extend(merged_results)

            # Convert all merged results for the next round
            converted_results = convert_for_next_round(merged_results)
            new_references.extend(converted_results)

        # Update references for the next round with all converted results
        references = new_references

    return min([o.src for o in references])


def process_all_rounds(rounds, references):
    """
    Process all rounds of conversion with multiple references and return the minimum src value.

    Args:
        rounds: List of lists of MyClass objects (7 rounds of objects).
        references: List of MyClass reference objects.

    Returns:
        int: Minimum src value from the final references after all rounds.
    """
    for i, round_objects in enumerate(rounds):
        # print(f"Processing Round {i + 1}...")

        # Process each reference independently
        new_references = []
        for ref in references:
            # print(ref)

            # Process the round and get merged results (both overlapping and uncovered)
            merged_results = process_round([ref], round_objects)

            # Convert all merged results for the next round
            converted_results = convert_for_next_round(merged_results)
            new_references.extend(converted_results)

        # Update references for the next round with all converted results
        references = new_references

    # Return the minimum src value from the final references
    return min([o.src for o in references])


# Example input

rounds = [
    [MyClass(src=98, dest=50, length=2), MyClass(src=50, dest=52, length=48)],
    [MyClass(src=15, dest=0, length=37), MyClass(src=52, dest=37, length=2), MyClass(src=0, dest=39, length=15)],
    [MyClass(src=53, dest=49, length=8), MyClass(src=11, dest=0, length=42), MyClass(src=0, dest=42, length=7), MyClass(src=7, dest=57, length=4)],
    [MyClass(src=18, dest=88, length=7), MyClass(src=25, dest=18, length=70)],
    [MyClass(src=77, dest=45, length=23), MyClass(src=45, dest=81, length=19), MyClass(src=64, dest=68, length=13)],
    [MyClass(src=69, dest=0, length=1), MyClass(src=0, dest=1, length=69)],
    [MyClass(src=56, dest=60, length=37), MyClass(src=93, dest=56, length=4)],
]


# Two reference inputs
references = [
    MyClass(src=79, dest=None, length=14),
    MyClass(src=55, dest=None, length=13),
]

# Process all rounds
results = process_all_rounds(rounds, references)
results
```

    46

``` python
def process_input(samp):
    seeds,*lines = samp.split('\n\n')
    seeds = L(seeds.strip().split(':')[1].split()).map(int)
    return seeds, linesb
```

``` python
data =get_data(day=5,year=2023)
```

``` python
seeds, lines = process_input(data)
```

``` python
def process(line): return L(line.split(':')[1].strip().split('\n')).map(lambda x: L(x.split()).map(int))
_lines = L(lines).map(process)
```

``` python
object_lines = _lines.map(lambda x: L(x).starmap(lambda dest,src,length: MyClass(src,dest,length)))
rounds = object_lines
```

``` python
seeds
```

    (#20) [222541566,218404460,670428364,432472902,2728902838,12147727,3962570697,52031641,2849288350,113747257,3648852659,73423293,4036058422,190602154,1931540843,584314999,3344622241,180428346,1301166628,310966761]

``` python
seeds[::2]
```

    (#10) [222541566,670428364,2728902838,3962570697,2849288350,3648852659,4036058422,1931540843,3344622241,1301166628]

``` python
references = [
    MyClass(src=src, dest=None, length=length)
    for src, length in zip(seeds[::2], seeds[1::2])
]
```

``` python
# Process all rounds
results = process_all_rounds(rounds, references)
results
```

    27992443
