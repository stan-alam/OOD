# OOD
Object Oriented Design/Programming

<a>
  <img src="https://github.com/stan-alam/OOD/blob/develop/Ruby/svg_files/Notebook-56.svg" width="80%" height="80%">
</a>

<a>
  <img src="https://github.com/stan-alam/OOD/blob/develop/Ruby/svg_files/Notebook-57.svg" width="80%" height="80%">
</a>

<a>
  <img src="https://github.com/stan-alam/OOD/blob/develop/Ruby/svg_files/Notebook-58.svg" width="80%" height="80%">
</a>

<a>
  <img src="https://github.com/stan-alam/OOD/blob/develop/Ruby/svg_files/Notebook-59.svg" width="80%" height="80%">
</a>

<a>
  <img src="https://github.com/stan-alam/OOD/blob/develop/Ruby/svg_files/Notebook-60.svg" width="80%" height="80%">
</a>

```Ruby

class Gear
  attr_reader :chainring, :cog
  def initialize(chainring, cog)
    @chainring = chainring
    @cog       = cog
  end

def ratio
  chainring / cog.to_f
  end
end

puts Gear.new(52, 11).ratio
puts Gear.new(30, 27).ratio

```

<a>
  <img src="https://github.com/stan-alam/OOD/blob/develop/Ruby/svg_files/Notebook-61.svg" width="80%" height="80%">
</a>

<a>
  <img src="https://github.com/stan-alam/OOD/blob/develop/Ruby/svg_files/Notebook-72.svg" width="80%" height="80%">
</a>
